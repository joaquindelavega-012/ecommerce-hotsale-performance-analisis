# Análisis de E-Commerce: Hot Sale 2017

### Descripción del proyecto
En este proyecto analizo los resultados de un e-commerce durante el Hot Sale de noviembre de 2017. El objetivo fue procesar las transacciones crudas para entender qué campañas de marketing fueron más rentables, qué canal trajo mejores resultados y cómo se comportaron las ventas a nivel geográfico y temporal.

### Herramientas utilizadas
* **Excel:** Para la limpieza inicial de los datos.
* **Google BigQuery (SQL):** Para procesar la información, unir las bases de datos y calcular métricas de negocio.
* **Looker Studio:** Para la visualización final de los datos en un dashboard.

### Resumen del proceso
Trabajé con varias tablas relacionales (clientes, órdenes, ítems y productos). Una vez limpios los datos, los subí a BigQuery donde armé consultas en SQL para cruzar la información y calcular métricas como el Retorno de Inversión (ROI) y el resultado neto de cada canal. Finalmente, conecté BigQuery con Looker Studio para graficar los resultados y facilitar su lectura.

### Resultados principales
A partir del análisis de más de 7.200 pedidos, encontré lo siguiente:

* **Eficiencia del Email Marketing:** Fue el canal más rentable. Con una inversión de solo $3.000 generó un nivel de ingresos similar al de Google Ads (que costó $15.000). El Email logró un ROI de 2.923%.
* **Pico de ventas:** El volumen no fue constante. El 24 de noviembre (Black Friday) hubo un pico masivo que concentró $175.178 en un solo día.
* **Concentración geográfica:** La región de São Paulo (SP) fue la que más traccionó, aportando casi el 35% de los ingresos totales del evento.
* **Categorías principales:** Hogar Textil y Relojes y Regalos fueron los rubros que más ingresos generaron.

### Archivos del repositorio
* `querys de sql.txt`: Todo el código SQL que escribí en BigQuery para limpiar y cruzar las tablas, incluyendo el análisis de ROI y tendencias.
* `Proyecto_E-commerce_.pdf`: El dashboard final exportado desde Looker Studio.
* `foto.jpg`: Un diagrama simple mostrando cómo conecté las distintas herramientas del proyecto.
