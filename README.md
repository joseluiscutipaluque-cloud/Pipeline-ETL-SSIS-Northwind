# Pipeline ETL con SSIS — Datamart Northwind

Pipeline ETL completo implementado con SQL Server Integration Services (SSIS) 
sobre la base de datos Northwind.

## Paquetes
- **Poblando_Stage.dtsx** → Extracción y transformación hacia el esquema Stage
- **Poblando_Dimension.dtsx** → Carga incremental al esquema Datawarehouse

## Tecnologías
SQL Server | SSIS | Visual Studio 2022 | T-SQL | Modelado Dimensional

## Estructura
- 7 dimensiones: Cliente, Empleado, Producto, Categoría, Proveedor, Tiempo y Transporte
- 1 tabla de hechos: Fact_Ventas
