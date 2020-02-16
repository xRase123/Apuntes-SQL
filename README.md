# Apuntes/SQL-JavierCamposAlvedro(ASI105)
Apuntes sobre SQL de la asignatura de Bases de Datos.
# Índice:
1. [Teoría Básica](#Teoría-Básica)
2. [Componentes del SQL](#Componentes-del-SQL)
3. [COMANDOS](#COMANDOS)
4. [SELECT](#SELECT)
5. [FROM](#FROM)
6. [WHERE](#WHERE)
7. [COUNT, AVG & SUM](#COUNT-AVG-SUM)
8. [JOIN](#JOIN)
9. [NULL](#NULL)
10. [SUBLENGUAJES](#SUBLENGUAJES)
11. [WebGrafía / Infografía](#WebGrafía-Infografía)

# Teoría-Básica
SQL (Structured Query Language) es un lenguaje declarativo de acceso a bases de datos relacionales que permite especificar diversos tipos de operaciones en ellas. Una de sus características es el manejo del álgebra y el cálculo relacional que permiten efectuar consultas con el fin de recuperar de forma sencilla información de interés de bases de datos, así como hacer cambios en ella.

El SQL es un lenguaje de acceso a bases de datos que explota la flexibilidad y potencia de los sistemas relacionales y permite así gran variedad de operaciones.

# Componentes-del-SQL
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

1.PNG

Donde WHERE reduce la lista proporcionada por el FROM (Y) y actúa sobre los datos del SELECT (X) a los nombres que coincídan con la cláusula proporcionada en el WHERE.

# COUNT-AVG-SUM
La función COUNT () devuelve el número de filas que coinciden con un criterio específico.
La función AVG () devuelve el valor promedio de una columna numérica.
La función SUMA () devuelve la suma total de una columna numérica.

EJEMPLO DE COUNT:
EJEMPLO DE AVG:
EJEMPLO DE SUM:
# JOIN
Una cláusula JOIN se usa para combinar filas de dos o más tablas, en función de una columna relacionada entre ellas.
EJEMPLO DE UN JOIN:

DIFERENTES JOIN's:

# NULL
Un campo con un valor NULL es un campo sin valor.

Si un campo en una tabla es opcional, es posible insertar un nuevo registro o actualizar un registro sin agregar un valor a este campo. Luego, el campo se guardará con un valor NULL.

EJEMPLO DE NULL:

# SUBLENGUAJES
Hay que de definir que lenguajes SQL existe 1, el mismo SQL, pero este a su vez está compuesto de 6 Sublenguajes

Sub – Lenguajes de SQL:
1.	- DQL (Data Query Language).		. Select,
2.	- DML (Data Manipulation Language).	. Select, Insert, Update, Delete
2.1	    	*DML Actúa sobre los Datos*
3.	- DDL (Data Definition Language)		. Create, Alter, Drop, Truncate
3.1    	 	*DDL Actúa sobre los objetos de la base de datos*
4.	- DCL (Data Control Language).		. Grant, Revoke 
5.	- TCL (Transacion Control Language).	. Commit, Rollback, Savepoint
6.	- SCL  (Session Control Language).		. Alter, Session

# WebGrafía-Infografía
1. [W3Schools](https://www.w3schools.com/sql/default.asp)
2. [SQLzoo](https://sqlzoo.net/wiki/SQL_Tutorial)
3. [Tsql](https://www.tsql.info/)
4. [Sublenguajes-SQL](https://mauricioaguilar1825.wordpress.com/sql/)
5. [Wikipedia-SQL](https://en.wikipedia.org/wiki/SQL)
