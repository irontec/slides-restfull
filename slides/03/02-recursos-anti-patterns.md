## Anti Patrones para Recursos

* GET http://api.example.com/services?op=actualizar_cliente&id=12345&format=json
    * Aunque la URL sea un nombre, no se corresponde al recurso en si.

* GET http://api.example.com/actualizar_cliente/12345
    * El recurso no es una URL
    * La acción no está en el método

* GET http://api.example.com/clientes/12345/actualizar
    * La acción no está en el método

* PUT http://api.example.com/clientes/12345/actualizar
    * La acción esta especificado 2 veces

    **¡¡¡ANTIPATRONES A EVITAR!!!**