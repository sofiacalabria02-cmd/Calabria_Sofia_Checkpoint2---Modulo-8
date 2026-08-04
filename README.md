# Calabria_Sofia_Checkpoint2---Modulo-8
Se configuró un modelo con relaciones activas de tipo Uno a Muchos (1:N) y dirección de filtro Única, utilizando las siguientes relaciones:
Dim_Clientes → Fact_Ventas mediante id_cliente.
Dim_Productos → Fact_Ventas mediante id_producto.
Dim_Fechas → Fact_Ventas mediante fecha_venta.
Nota: En el checkpoint anterior se realizó un Merge entre Fact_Ventas y Dim_Productos, incorporando las columnas nombre_producto y categoria a la tabla de hechos. Por este motivo, la tabla Dim_Categorias no participa del modelo relacional final.

Se creo la tabla calendario.

Se creó una tabla exclusiva llamada _Medidas para organizar todos los indicadores del modelo.

Se creó una matriz para comprobar el correcto funcionamiento de las medidas.

Se obtuvo un modelo de datos con estructura tipo estrella, preparado para el desarrollo de dashboards e indicadores de negocio. La incorporación de una tabla calendario y medidas DAX permite realizar análisis temporales, comparaciones entre períodos y cálculos de KPIs que servirán como base para el proyecto integrador del curso.
