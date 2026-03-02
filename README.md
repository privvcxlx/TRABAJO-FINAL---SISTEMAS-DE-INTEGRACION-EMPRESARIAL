# TRABAJO-FINAL---SISTEMAS-DE-INTEGRACIÓN-EMPRESARIAL

Proyecto integral de BI que abarca desde la extracción de datos crudos hasta la visualización estratégica para la toma de decisiones financieras.

## Arquitectura de la Solución
El proyecto sigue el flujo completo de una solución de Inteligencia de Negocios:

1.  **SQL Server (Data Warehouse)**: Diseño de un modelo estrella (`Fact_Ventas`, `Fact_Pagos`) con integridad referencial.
2.  **SSIS (ETL)**: Paquetes de integración para la limpieza y carga de datos desde orígenes heterogéneos.
3.  **SSAS (Cubo OLAP)**: Modelado multidimensional para análisis de KPIs (Ventas totales, Deuda pendiente, Margen).
4.  **Python (Analítica Avanzada)**: Análisis exploratorio (EDA) y Clustering (K-Means) para segmentar clientes por riesgo financiero.

## Resultados Clave
* Identificación de brechas de recaudo mediante análisis de correlación.
* Segmentación automatizada de clientes.
