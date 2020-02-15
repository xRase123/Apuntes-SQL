# Apuntes/SQL-JavierCamposAlvedro(ASI105)
Apuntes de Bases de Datos.
# Índice:
1. Teoría Básica
2. Componentes del SQL
3. COMANDOS
4. SELECT
5. FROM
6. WHERE
7. SUM & COUNT
8. JOIN
9. NULL
# Teoría Básica:
SQL (Structured Query Language) es un lenguaje declarativo de acceso a bases de datos relacionales que permite especificar diversos tipos de operaciones en ellas. Una de sus características es el manejo del álgebra y el cálculo relacional que permiten efectuar consultas con el fin de recuperar de forma sencilla información de interés de bases de datos, así como hacer cambios en ella.

El SQL es un lenguaje de acceso a bases de datos que explota la flexibilidad y potencia de los sistemas relacionales y permite así gran variedad de operaciones.
# Componentes del SQL
El lenguaje SQL está compuesto por comandos, cláusulas, operadores y funciones de agregado. Estos elementos se combinan en las instrucciones para crear, actualizar y manipular las bases de datos.
# COMANDOS
Existen tres tipos de comandos SQL:

Los DLL(Data Definition Language) que permiten crear y definir nuevas bases de datos, campos e índices. Los DML(Data Manipulation Language) que permiten generar consultas para ordenar, filtrar y extraer datos de la base de datos. Los DCL(Data Control Language) que se encargan de definir las permisos sobre los datos
# SELECT
La instrucción SELECT se usa para seleccionar datos de una base de datos.

Los datos devueltos se almacenan en una tabla de resultados.

EJEMPLO DE SELECT:
SELECT X
FROM Y
WHERE ...

Donde X debe ser sustituído por el nombre de una columna de la tabla referenciada en Y
# FROM
El comando FROM se usa para especificar de qué tabla seleccionar o eliminar datos.

EJEMPLO DE FROM:
SELECT X
FROM Y 
WHERE ...

Donde Y referencia una tabla compuesta por Columnas (X) que son llamadas con el SELECT.
# WHERE
La cláusula WHERE se usa para filtrar registros.

La cláusula WHERE se usa para extraer solo aquellos registros que cumplen una condición específica.

![GitHub Where Clause] (/descargas/Github images/1.png)
Format : ![Alt Text](url)

Donde WHERE reduce la lista proporcionada por el FROM (Y) y actúa sobre los datos del SELECT (X) a los nombres que coincídan con la cláusula proporcionada en el WHERE.
# SUM & COUNT
