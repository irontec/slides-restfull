## Filtros / Búsquedas
#### (buena práctica)

* Es recomendable utlizar un único campo a la hora de filtrar una colección de recursos.
* El objetivo es mantener la URL simple y entendible.

* Propuesta: Utilizar el nombre del campo como parámetro;
    * (limitarlo a una lista blanca, y documentarlo)

````http
GET /pedidos/?estado=enviados
````


* Otra práctica recomendable crear **alias** que realicen búsquedas más complejas pero habituales

````http
GET /pedidos/ganados_semana
````
