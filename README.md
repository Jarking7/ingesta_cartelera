# ingesta_cartelera
Codigo de lambda para ingresar datos a una tabla DynamoDB


En este repositorio tenemos alojado el codigo utilizado en la lambda ingestadatos_cartelera_jafet, la cual se encarga principalmente de añadir datos a una tabla de DynamoDB previamente creada por el grupo donde la clave de particion es 'pelicula_id' y la
clave de ordamiento es 'fecha_hora'.

Otros atributos que se encuentran dentro de la tabla son: nombre, sala, duraciòn y clasificaciòn. 


Una vez añadimos todos estos atributos a nuestra lambda y verificamos nuestro codigo, procedemos a crear 5 eventos, corresponientes a los id asignados a cada uno.

Creado cada evento, se invoca la lambda y esta misma, ingresa los valores a la tabla Peliculas_S3D2_xideral.

Posteriormente, verificamos con ayuda de un notebook de Jupyter que los datos hayan sido ingresado de manera correcta a la tabla.

Con esto podemos finalizar este ejercicio.

:)
