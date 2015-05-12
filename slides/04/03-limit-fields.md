## Limitar campos
#### (buena práctica)

* Puede optimizar el uso de la red, ya que no siempre será necesaria recuperar una representación exacta del recurso:

* Propuesta: Utilizar el parámetro fields para especificar que campos se quiere recuperar en la representación.


````http
GET /pedidos?fields=id,date,amount
````

