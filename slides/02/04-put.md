## PUT

* Su utilidad más extendida será la de actualizar un recurso concreto.

* Podría usarse para crear entidades en un sistema donde el ID es escogido por el usuario
    * No es muy recomendable por *raro*

* La respuesta podría ser un 200 ó un 204. No es necesario una redirección ya que el usuario ya conoce el ID del recurso.

* No es una operación segura (modifica el estado de un recurso)

* Puede considerarse idempotente.
    * (a no ser que se agrege un contador o se modifique una fecha)

<hr />

    PUT http://www.example.com/clientes/12345
    PUT http://www.example.com/clientes/12345/pedidos/98765
    PUT http://www.example.com/presupuestos/1234
