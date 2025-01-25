# TP Final - Argentina Ideal

Este proyecto consiste en el desarrollo de una infraestructura y soluciones utilizando herramientas de Google Cloud para gestionar y analizar datos de ventas, stock, deudas y clientes de la empresa "Argentina Ideal". El objetivo principal es implementar un sistema eficiente para generar, almacenar y visualizar datos clave que permitan tomar decisiones basadas en indicadores específicos de negocio.

## Enunciado del proyecto

"Argentina Ideal" es una empresa de producción y venta de productos masivos que organiza sus ventas en el territorio argentino mediante distribuidores. Estos distribuidores manejan la toma de pedidos, el reparto y la facturación, conectando a la empresa con los comercios minoristas (almacenes, supermercados, free-shops, entre otros).

La empresa busca optimizar sus procesos y obtener información clave sobre sus operaciones a partir de datos enviados diariamente por los distribuidores. Esto incluye información sobre:
- Ventas realizadas
- Deudas de clientes
- Stock disponible
- Clientes registrados

## Objetivos

1. Completar el **diagrama del flujo de información** centrado en los datos enviados por los distribuidores.
2. Crear el **diagrama del ciclo de vida de los datos**.
3. Implementar una solución que utilice los siguientes servicios de Google Cloud:
   - **Cloud Storage**: Almacenamiento de archivos CSV enviados por los distribuidores.
   - **BigQuery**: Análisis y explotación de datos almacenados.
   - **Cloud Composer**: Automatización de procesos ETL.
   - **Data Studio**: Visualización de indicadores clave mediante tableros interactivos.

## Indicadores clave

### Marketing
- **Volumen de ventas**: Permitir la selección por región y rango de fechas.

### Suministros
- **Stock diario**: Visualización del stock de productos por distribuidor.

### Finanzas
- **Deudas semanales**: Mostrar la deuda de los clientes con los distribuidores, filtrable por distribuidor y rango de fechas.

## Herramientas utilizadas

- **Google Cloud Storage**: Para almacenar los datos enviados por los distribuidores.
- **Google BigQuery**: Para la consulta y análisis de grandes volúmenes de datos.
- **Google Cloud Composer**: Para automatizar procesos ETL y asegurar flujos de datos consistentes.
- **Google Data Studio**: Para crear tableros de control que presenten los indicadores clave.

