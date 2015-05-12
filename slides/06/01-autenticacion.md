## Autenticación

* Basándonos en el principio 2 de REST, **STATELESS**, cada petición a la API, deberá contener las credenciales autenticadas.

* La autenticación viaja generalmente en la cabecera **Authorization** de la petición.

* Existen multitud de posibilidades para autenticar cada petición.
* Deberemos implementar la que satisfaga nuestra necesidad de seguridad
    * ¿estamos siempre sobre SSL?
    * ¿tenemos usuario públicos?
    * ¿estamos en una intranet?