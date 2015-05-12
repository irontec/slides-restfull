## OAUTH2
### Autenticación

* El problema con HMAC, es que se basa en un secreto compartido.
* Si el secreto se descubre, el servicio queda *expuesto*

<hr />

* La base de OAuth es crear token temporales para autenticar.

* Oauth2 delega en un tercero la autenticación.
* El tercero debe permitir la integración.
* El usuario debe permitir que el tercero valide su identidad en nuestro servicio.
* OAuth2 se basa en la generación de un token de refresco, que generará tokens temporales.
* El extremo del servidor validará cada petición contra el tercero.

* El usuario puede revocar el permiso en la aplicación del tercero en cualquier momento.
