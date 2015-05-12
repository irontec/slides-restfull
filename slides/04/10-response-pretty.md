#Response Pretty

* JSON puede estár minificado y ahorrar espacio:
````javascript
{'id':12345,'ammount':'34€','date':'2015-04-12 13:33:33+01:00','cliente' : {'nombre' : 'Jabi','email':'jabi@irontec.com'}}
````

* O ser bonito y leible:
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

* Siempre que el contenido esté comprimido a nivel HTTP, es más usable la segunda opción, ya que lo hace mucho más **accesible** y fácilmente **consumible**.

