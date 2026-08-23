
# Guía de Autoestudio 2/6: SQL Básico
**Asignatura:** Modelos y Servicios de Datos [MYSD-MBDA]
**Periodo:** 2026-2

---

## 🎯 Objetivos de la Guía
Desarrollar competencias básicas para escribir consultas en **SQL**, considerando:
- El tratamiento y valor asignado a lo desconocido (`NULL`).
- Operaciones entre conjuntos.
- Construcción de juntas explícitas (*Joins*).

---

## 📋 Puntos a Resolver

### 1. Investigación Teórica
> ⚠️ **Nota:** Recuerda incluir la bibliografía consultada.

* **Sección A: El Valor NULL**
  1. ¿Qué significa `NULL`?
  2. ¿Cuál es el resultado de operarlo con los diferentes tipos de operadores (aritméticos, lógicos y de comparación)?

* **Sección B: Juntas (Joins)**
  1. ¿Cuáles son las diferencias entre junta interna (*Inner Join*) y externa (*Outer Join*)?
  2. ¿Qué opciones se tienen para la junta interna?
  3. ¿Qué opciones se tienen para la junta externa?

---

### 2. Práctica
> 📁 **Ubicación de respuestas:** Todas las soluciones de esta sección deben quedar consolidadas en el archivo `auto02.pdf`.

* **Parte A: W3Schools SQL Tutorial**
  * Estudiar las secciones: *SQL Join, SQL Inner Join, SQL Left Join, SQL Full Join, SQL Self Join, SQL Null Functions, SQL Union, SQL Exists, SQL Any/All, SQL Case*.
  * Escoger **5 ejemplos** y escribir sus sentencias equivalentes en **Cálculo** o **Álgebra Relacional**. 
  *(Si no se logró escribir alguna sentencia, indicar la razón y el punto exacto de dificultad).*

* **Parte B: Ejercicios en SQLZoo.net (Motor MySQL)**
  * Realizar los ejercicios y quices propuestos en los siguientes tutoriales:
    * `JOIN` + Quiz
    * `More JOIN` + Quiz
    * `Using NULL` + Quiz
    * `Self JOIN` + Quiz
  * Escribir las sentencias SQL ejecutadas y los puntajes de los quices en `auto02.pdf`.

* **Parte C: Propuesta de Consultas (Base de Datos *Musicians*)**
  * Diseñar y redactar la consulta en lenguaje natural y su correspondiente sentencia en SQL para:
    * 📄 **5 consultas:** Una para cada operador de conjuntos (`UNION`, `UNION ALL`, `INTERSECT`, etc.).
    * 📄 **6 consultas:** Una para cada operador de junta (`INNER`, `LEFT`, `RIGHT`, `FULL`, `NATURAL`, `CROSS`).
    * 📄 **2 consultas:** Una para cada operador de desconocido (`IS NULL`, `COALESCE`).
    * 📄 **3 consultas:** Una para cada uno de los tipos de operadores lógicos (`EXISTS`, `ANY`, `ALL`).
    * 📄 **1 consulta:** Para el operador condicional `CASE`.

---

## 📦 Instrucciones de Entrega
* Publicar las respuestas en un archivo comprimido **`.zip`**.
* **Nomenclatura del archivo:** Concatenación en **orden alfabético** de los primeros apellidos de cada uno de los miembros del equipo (ej. `Apellido1_Apellido2.zip`).
