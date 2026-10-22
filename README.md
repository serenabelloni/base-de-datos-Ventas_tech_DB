# RetailPro — Base de datos de ventas

## Descripción del proyecto

RetailPro es un proyecto académico de análisis de datos orientado a la gestión y el análisis de ventas de un negocio minorista. Se desarrolló una base de datos en SQL Server para organizar información comercial y realizar consultas que permitan responder preguntas del negocio.

El proyecto forma parte del curso de Data Analytics de Coderhouse y utiliza la base de datos `Ventas_Tech_DB`.

## Objetivos

- Diseñar y consultar una base de datos relacional.
- Relacionar información de ventas, clientes, productos y categorías.
- Identificar clientes sin compras y productos sin ventas.
- Analizar la facturación y el comportamiento comercial mediante consultas SQL.

## Herramientas utilizadas

- **Microsoft SQL Server:** motor de base de datos.
- **GitHub:** plataforma para guardar y documentar el código del proyecto.
- **Power BI:** herramienta complementaria para preparar y visualizar información, cuando corresponda a los archivos incluidos en el proyecto.

## Estructura de la base de datos

El proyecto trabaja con las siguientes tablas principales:

- `ventas`: información de las ventas, fechas, cantidades y precios.
- `clientes`: información de los clientes.
- `productos`: información de los productos comercializados.
- `categorias`: clasificación de los productos.
- `territorios`: información sobre donde ocurren las ventas.
- 

Las relaciones entre las tablas permiten combinar datos para obtener información comercial más completa.

## Consultas SQL desarrolladas

Las consultas del proyecto permiten:

1. Obtener el detalle de las ventas con información del cliente, producto y categoría mediante `INNER JOIN`.
2. Identificar clientes que no registran compras mediante `LEFT JOIN`.
3. Detectar productos que no registran ventas.
4. Consolidar información de ventas por canal utilizando `UNION ALL`.
5. Calcular la facturación total por canal mediante funciones de agregación como `SUM`.

## Cómo ejecutar los scripts

1. Clonar o descargar este repositorio desde GitHub.
2. Abrir SQL Server Management Studio y conectarse a la instancia de SQL Server utilizada para el proyecto.
3. Seleccionar la base de datos `Ventas_Tech_DB`.
4. Abrir el archivo `.sql` que se desea ejecutar.
5. Verificar que la base de datos y las tablas necesarias existan antes de ejecutar la consulta.
6. Ejecutar el script y revisar los resultados en la pestaña **Resultados**.

**Importante:** si la base de datos todavía no existe, primero se deben ejecutar los scripts de creación de la base de datos y de sus tablas, y luego cargar los datos necesarios. Los scripts de análisis dependen de que esas estructuras y datos estén disponibles.

## Requisitos

- Una instancia de Microsoft SQL Server.
- SQL Server Management Studio u otra herramienta compatible con SQL Server.
- La base de datos `Ventas_Tech_DB` creada y con los datos necesarios para ejecutar las consultas.

## Autora

Proyecto desarrollado individualmente en el marco del curso de Data Analytics de Coderhouse.

## Repositorio

[Base de datos Ventas_Tech_DB en GitHub](https://github.com/serenabelloni/base-de-datos-Ventas_tech_DB)
