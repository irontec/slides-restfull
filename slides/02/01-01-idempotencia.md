## Idempotencia

* Desde un punto de visto REST, una operación **idempotente** es aquella que pese a ser invocada varias veces, produce siempre el mismo resultado.

    * GET
    * HEAD
    * OPTIONS
    * TRACE

    * DELETE (Aunque no cambie el estado del servidor, la respuesta no es idéntica)
    * PUT (Depende de la implementación)