## Limitar Relaciones
#### (buena práctica)

* Es bastante común que al recuperar un recurso, el usuario necesite recuperar otros recursos relacionados.
* Aunque no sería RESTFULL, minimizamos el número de peticiones.

* Propuesta: Utilizar el parámetro "expand"

````http
GET /pedidos/12345?exand=cliente.nombre,cliente.email
````

La respuesta sería:

````javascript
{
    'id':12345,
    'ammount':'34€',
    'date':'2015-04-12 13:33:33+01:00',
    'cliente' : {
        'nombre' : 'Jabi',
        'email': 'jabi@irontec.com'
    }
}
````