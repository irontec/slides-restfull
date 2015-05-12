## GET

* Se utiliza para leer uno o varias reprsentaciones de recursos.

* No debería cambiar el estado de ningún recurso en el servidor

* Podrá ser invocada 100 veces y siempre se conseguriá la misma representación (_idempotente_)

<hr />

    GET http://www.example.com/clientes/12345

    GET http://www.example.com/clientes/12345/pedidos

    GET http://www.example.com/presupuestos


