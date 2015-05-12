## Paginacion
#### (buena práctica)

* Propuesta: Utilizar parámetro "page" para especificar 

* Existe un RFC que especifica como devolver información de paginación en la cabecera.
([Enlace ietf](http://tools.ietf.org/html/rfc5988#page-6))

````http
Link: <https://api.github.com/user/repos?page=3&per_page=100&gt;; rel="next", <https://api.github.com/user/repos?page=50&per_page=100&gt;; rel="last"
````
