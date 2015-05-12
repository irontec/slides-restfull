## Orden
#### (buena práctica)

* Para solicitar una colección ordenada con respecto a uno o varios campos, de manera ascendiente o descendiente


* Propuesta: Utilizar el parámetros "sort"
    * Separar por comas los campos a tener en cuenta para ordenar
    * Utilizar un signo negativo si la ordenación debe ser descendiente

````http
GET /pedidos/?orden=-date,importe
````