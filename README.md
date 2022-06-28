# Reporteía en Excel

**Descripción**
Reporte en Excel para análisis de información relevante, utilizando datos de ventas, producción, ingresos y costos con diferentes categorías para discriminar. Se presenta una visualización amigable para el usuario, a partir del uso de tablas dinámicas, así como herramientas condicionales y de segmentación de datos. útiles al momento de interactuar con grandes cantidades de información.


## Informe de Ventas

Informe que presenta información de ingresos totales obtenidos durante un período determinado, en este caso un año. En segundo lugar, se ofrece información segmentada por las categorías de **Región**, **Producto** y **Vendedor**. Dentro de cada categoría se ofrece información de aquellos montos mayores y menores dentro de cada categoría, con sus respectivas visualización para simplificar y comprender mejor el análisis. Finalmente, se disponen de filtros, los cuales permiten segmentar según las categorías mencionadas anteriormente y cada elemento dentro de ellas.

![Informe de Ventas]
(/Assets/Informe_de_Ventas.png)

## Informe de Finanzas

Informe que presenta información acerca de los ingresos y las utilidades obtenidas durante un período determinado, en este caso un semestre separado en meses. Se presenta mediante el desglose de tres informes complementarios:

* Informe de Ingresos : Informe que engloba las principales fuentes de ingreso, separadas por categorías de **Región** y **Tipo de Producto**. Adicionalmente, visualiza dicha información en las 5 prinipales fuentes de ingreso y su evolución durante el semestre, según el **Cliente**, **Tipo de Producto** o **Producto**, y un gráfico que muestra los ingresos por **Región** de manera sencilla.

![Informe de Ingresos]
(https://raw.githubusercontent.com/figuearlt/Reporter-a-en-Excel/master/Assets/Reporte de Ingresos.png)

* Informe de Utilidad y Margen por Región y Cliente : Informe con enfoque en la información sobre la **Utilidad** y el **Margen** obtenido, así como su evolución en el tiempo. También se evalúa aquellas **Regiones** con mayores ingresos en términos de montos nominales y proporcionales, pudiendo segmentar dicha información por el **Tipo de Producto**, distinguiendo cuáles regiones obtienen mejor o peor desempeño en dicho producto, así como su evolución durante el semestre.

![Informe de Utilidad y Margen por Región y Cliente]
(https://raw.githubusercontent.com/figuearlt/Reporter-a-en-Excel/master/Assets/Reporte de Utilidad por Región.png)

* Informe de Utilidad y Margen por Tipo de Producto : Informe con enfoque en la información acercade la **Utilidad** y el **Margen** obtenido, así como su evolución en el tiempo. Se distingue del anterior, ya que este ofrece una segmentación por **Región**, pudiendo evaluar aquellos **Tipos de Productos** que tuvieron un mejor desempeño durante el semestre, por ejemplo, para el caso de Argentina. Adicionalmente, puedo desagregar la información del **Tipo de Producto++, y obtener información sobre los montos de ingresos nominales por cada **Producto**

![Informe de Utilidad por Tipo de Producto]
(https://raw.githubusercontent.com/figuearlt/Reporter-a-en-Excel/master/Assets/Reporte de Utilidad por Producto.png)

### Informe de Producción

Informe tipo *Dashboard*, el cual ayuda para monitorear y tomar decisiones en base a los nuevos registros de órdenes que se vayan realizando. El informe entrega un histórico, durante un año, sobre órdenes y *status*.
En primer lugar, el informe puede segmentarse en base al **Status** del producto, es decir, si es un producto **Devuelto** o **Entregado**, o ver ambas a modo de producción total. Con ello nos ofrece información sobre su producción y las órdenes de compra para estas, y visualiza el porcentaje de entregas sobre el total producido. En segundo lugar, se viasualiza información sobre qué **Gerentes** tuvo un mejor desempeño de ventas entregadas o aquel que tuvo mayores devoluciones; qué **Tipo de Cliente** tuvieron más piezas producidas; qué productos según el **Tipo de Prioridad** de entrega fueron devueltas o vendidas.
Por último, se presenta un segundo informe con mayor detalle sobre las razones de las devoluciones, segmentado por las mismas categorías anteriores.

![Informe de Producción] (https://raw.githubusercontent.com/figuearlt/Reporter-a-en-Excel/master/Assets/Informe_de_Produccion.png)

![Informe de Devoluciones] (https://raw.githubusercontent.com/figuearlt/Reporter-a-en-Excel/master/Assets/Informe_de_Devolucion.png)

