## CORS
###Cross-Origin Resource Sharing

* Mecanismo que permite a un servicio REST, *validar* el origen de una petición.

1. En la petición, el navegador enviará:
````http
Origin: http://www.foo.com
````

2. El servidor deberá enviar:
````http
Access-Control-Allow-Origin: http://www.foo.com
````
En caso contrario, la petición no tendrá éxito.




