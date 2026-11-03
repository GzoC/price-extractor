# price-extractor

Idea de un extractor visual de precios y stock. El proyecto se cerró en la etapa de propuesta. La versión original contiene la descripción de la idea, la licencia y la configuración de Git. No llegó a publicarse código de extracción, datos ni una demostración. [Versión original](https://github.com/GzoC/price-extractor/tree/0d8e112f415f2e179f829837998fdad1afe78e61)

## Backlog de abastecimiento industrial

Una posible aplicación sería ayudar a mantenimiento a comparar ofertas del mismo repuesto. Para que una cotización sea comparable, hace falta distinguir el precio unitario del precio por caja y la disponibilidad confirmada de un dato ausente.

Si se retoma la idea, el caso mínimo por demostrar sería el siguiente.

1. **Entrada.** Partir de dos cotizaciones de ejemplo cuyo uso y publicación estén autorizados. Identificar proveedor, fecha, referencia del fabricante y unidad de venta.
2. **Extracción.** Leer precio, moneda, cantidad por envase y disponibilidad. Guardar la página o fila de origen para poder contrastar cada valor.
3. **Validación.** Comparar solo referencias equivalentes con la misma moneda y unidad. Conservar los datos ausentes y enviar a revisión las lecturas ambiguas.
4. **Historial.** Guardar cada observación con su fecha y procedencia para reconstruir una comparación sin sobrescribir las cotizaciones anteriores.
5. **Resultado.** Mostrar qué oferta tiene el menor precio unitario entre las que declaran stock y señalar cuándo faltan datos para decidir.

Este backlog conserva el propósito del proyecto. Los pasos anteriores describen trabajo futuro.

## Trabajo relacionado

El ejercicio de **Books to Scrape** sí incluye un lector de fichas, una muestra, pruebas y un notebook ejecutado. Para un caso aplicado a activos, repuestos y costos, consulta el proyecto de analítica SQL de mantenimiento. [Ejercicio de scraping](https://github.com/GzoC/project_webscraping_01) · [Analítica SQL de mantenimiento](https://github.com/GzoC/my_sql_project_01)
