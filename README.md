
# sistemas para una zapateria 

## Modelo Entidad_relacion

![modelo entidad_relacion](img/draw.png "Modelo entidad-relacion")

## Modelo Fisico de la BD

![modelo fisico](img/bdmyslq1.png "modelo fisico de la Bd")

## tabla fabricante

![tabla fabricante](img/calcin.png "tabla fabricante")

## articulo 
![articulo](img/zap.png "articulo")

## consultas a la bd

1. Mostrar la lista de todos datos de los fabricantes

`SELECT * FROM fabricante;`

2. Mostrar la lista de nombres de los fabricantes 

`SELECT nombre_fabricante AS fabricante FROM fabricante;`

![consulta](img/from.png "consulta2")

3. Mostrar los nombres de los productos.

`SELECT nombre_articulo FROM * articulo`

![consulta3](img/nameart.png "consulta3")

4. mostrar los precios de los nombres de los productos

`SELECT nombre_articulo AS Nombre, precio_articulo AS Precio FROM Articulo;`

![consulta4](img/aja.png)

5. Obtener los nombres de los articulos cuyos precios son mayores a 50000

![consulta5](img/5.png)

6. Obtener el nombre de los articulos entre los precios 5000 y 40000 (ambos incluidos)

`SELECT nombre_articulo FROM articulo WHERE precio_articulo >= 5000 AND precio_articulo <= 40000;`

![consulta6](img/6.png)