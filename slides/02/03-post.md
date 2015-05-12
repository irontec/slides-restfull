## POST

* Verbo utilizado para crear nuevos recursos

* La respuesta podría ser un 201 (created), y una cabecera de redirección hacia el nuevo recurso

* No es idempotente, ni seguro. Si es invocado 2 veces, seguramente se crearán dos recursos con la misma información.

<hr />

    POST http://www.example.com/clientes
    POST http://www.example.com/clientes/12345/pedido
