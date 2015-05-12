##Last-Modified
###Cacheo

* La API deberá incluir en la respuesta una cabecera **Last-Modified** con la fecha de última modificación del recurso.

* El cliente almacena la fecha asociado a la URI

* En la próxima petición a ese mismo recurso, se añade a la petición la cabecera **If-Modified-Since:**

* Si el contenido no ha sido modificado, la API devolverá un **304 Not Modified**.