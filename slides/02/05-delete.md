## DELETE

* Se utiliza para eliminar uno  varios recursos
* No es seguro ya que cambia el estado del servidor.

* La respuesta más habitual sería un 204 (No data).

* DELETE se considera idempotente en el caso que la API marque los recursos como "borrados".
    * Si se realiza un borrado lógico, se responsería un 404; por lo que dejaría de ser un método idempotente.

<hr />


    DELETE http://www.example.com/clientes/12345
    DELETE http://www.example.com/clientes/12345/pedidos