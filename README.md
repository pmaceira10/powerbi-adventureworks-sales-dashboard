# Power BI – Advanced Sales Dashboard

Proyecto correspondiente a la práctica de nivel avanzado en Power BI.  
El objetivo es construir un modelo de datos sólido, aplicar transformaciones complejas en Power Query y desarrollar medidas DAX avanzadas para analizar las ventas de una empresa con dos canales de distribución: reseller e Internet.

## Objetivos del proyecto

- Cargar y modelar un fichero de ventas con incidencias de integridad.  
- Ajustar el modelo y las consultas de Power Query para garantizar la actualización correcta de los datos.  
- Crear un modelo unificado que permita analizar ventas por diferentes dimensiones geográficas y de cliente.  
- Desarrollar medidas DAX que permitan comparativas temporales y análisis detallado por cliente y periodo.  
- Diseñar visualizaciones limpias, coherentes y funcionales que comuniquen los principales indicadores de negocio.

## Modelado y Power Query

- Carga inicial del fichero principal de ventas.  
- Ajuste de relaciones y detección de errores de integridad al refrescar con un segundo conjunto de datos.  
- Unificación del concepto de cliente para integrar ambos canales de venta.  
- Preparación de tablas de referencia para geografía, productos y clientes.

## DAX y medidas calculadas

- Creación de una tabla calendario y funciones de tiempo (comparativas año/mes anterior).  
- Implementación de un doble calendario para comparar dos periodos distintos de ventas.  
- Cálculo de métricas de rendimiento y ratios entre periodos.  
- Identificación dinámica del cliente con mayor volumen de compra según los filtros aplicados.  
- Creación de una tabla de responsables comerciales filtrable por país.

## Visualizaciones

- Diseño estructurado siguiendo buenas prácticas de análisis visual.  
- Incorporación de visualizaciones geográficas para analizar la distribución de ventas por país.  
- Inclusión de imágenes representativas (banderas, categorías o productos) para mejorar la presentación.  
- Utilización de al menos diez tipos de visualizaciones diferentes con un formato coherente y profesional.

## Sección de bicicletas

Se incluyó una página dedicada exclusivamente a la categoría de bicicletas, en la que se analizan:
- Las bicicletas más vendidas.  
- La evolución de las ventas a lo largo del tiempo.  
- Los colores más vendidos dentro de la categoría.
