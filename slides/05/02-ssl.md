## SSL

* Utilizar SSL **siempre**.

* Facilita el sistema de autenticación, ya que se delega el cifrado de las credenciales en la capa de transporte.

* No redirigir desde HTTP a HTTPs; es mejor mostrar un error, y que **NO** funcione.
    * De otra manera, las peticiones HTTP *SI* funcionarían y viajarían (al menos una vez), en claro.
