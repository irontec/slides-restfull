## Evitar Envoltorio (Wrap)
#### (buena práctica)

* Evitar cuando sea posible, envolver los datos en una estructura _extra_.
    * overhead innecesario
    * metadatos en cabeceras

````javascript
{
    'id':'12',
    'ciudad':'bilbao'
}
````


### Excepciones
* JSONP: El cliente no soporta CORS
    * La petición viaja con un parámetro **jsonp=metodo_callback**
    * La API devolverá siempre un status Code *200*

````javascript
metodo_callback({
    status_code: 200,
    next_page: "https://..",
    response: {
        'id':'12',
        'ciudad':'bilbao'
    }
});
````

