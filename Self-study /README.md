# 🎵 Laboratorio 1: Diseño Conceptual General y SQL-DQL Básico

**Asignatura:** Modelos y Servicios de Datos (MYSD)  
**Institución:** Escuela Colombiana de Ingeniería Julio Garavito  
**Período:** 2026-2  
**Motor de BD / Entorno:** MySQL (Sage) via [SQLZoo.net](https://sqlzoo.net/) / Astah  

---

## 👨‍💻 Integrantes del Equipo

* **Integrante 1:** Apellido, Nombre
* **Integrante 2:** Apellido, Nombre  
> **Nombre del archivo comprimido de entrega:** `Apellido1-Apellido2.zip`

---

## 🎯 Objetivos del Laboratorio

1. **Ingeniería Inversa:** Construir el modelo lógico y conceptual a partir de una base de datos relacional existente (*Musicians*).
2. **Formulación de Consultas:** Diseñar e implementar consultas gerenciales y operativas orientadas a la toma de decisiones.
3. **Múltiples Lenguajes de Consulta:** Implementar consultas (simples y anidadas) en **Álgebra Relacional**, **Cálculo Relacional** y **SQL**.

---

## 🛠️ Estructura del Trabajo

El laboratorio se divide en cuatro partes principales y una retrospectiva:

### 📌 PARTE I. Conociendo la Organización
* **A. Contenido (Easy Questions):**
  * Conteo total de músicos, compositores e intérpretes.
  * Tipos de bandas y distribución.
  * Fechas extremas de composición (más antigua y más reciente).
  * Conciertos por año (ordenados de mayor a menor).
  * Frecuencia de canciones interpretadas más de una vez.
  * Pregunta propuesta y su correspondiente solución.
* **B. Contexto de la Organización:**
  * Misión de la organización *Musicians*.
  * Servicios ofrecidos a los clientes.
  * Definición de 3 usuarios clave, sus roles y responsabilidades (Diagrama de Casos de Uso en Astah).

### 📌 PARTE II. Diseñando - Ingeniería Inversa
* **Modelo Lógico Mínimo:** Validación del esquema con restricciones de PK, FK y UK (Diagrama de clases en `musicians.astah`).
* **Diagrama de Conceptos:** Representación conceptual sin atributos mostrando las relaciones del dominio.

### 📌 PARTE III. Implementación de Consultas
* **Consultas Básicas:** Solución a *Easy Questions* representadas en **Álgebra Relacional**, **Cálculo Relacional** y **SQL**.
* **Consultas Intermedias:** Solución a *Medium Questions* mediante sentencias SQL en SQLZoo.

### 📌 PARTE IV. Consultas Gerenciales y de Misión
1. **Métrica de Misión:** Consulta SQL justificada para medir el grado de cumplimiento de la misión organizacional.
2. **Propuesta de Mejora:** Pregunta crítica para la gestión que no puede responderse actualmente y los cambios requeridos en el modelo de datos.
3. **Consulta por Actor:** Consulta orientada a satisfacer la necesidad de uno de los usuarios identificados en el contexto.

---

## 🔄 Retrospectiva del Proyecto

| # | Pregunta | Respuesta |
|---|---|---|
| **1** | **Tiempo total invertido por cada integrante (Horas)** | • Integrante 1: X horas<br>• Integrante 2: X horas |
| **2** | **Estado actual del laboratorio y por qué** | [Completado / En desarrollo]. Se completaron las consultas y el modelado en Astah. |
| **3** | **Práctica XP más útil y por qué** | **Pair Programming:** Nos permitió validar las consultas en SQLZoo y diseñar el modelo lógico en Astah evitando errores de sintaxis. |
| **4** | **Mayor logro y por qué** | Mapear correctamente la estructura de la BD *Musicians* mediante ingeniería inversa hacia el modelo conceptual. |
| **5** | **Mayor problema técnico y solución** | [Describir el problema]. Se resolvió consultando la documentación de MySQL en SQLZoo y ajustando los `JOIN`. |
| **6** | **Trabajo en equipo y compromisos** | **Bien:** Comunicación fluida y división clara del análisis.<br>**Compromiso:** Mejorar la gestión del tiempo en la elaboración de diagramas Astah. |
| **7** | **Referencias utilizadas** | • Date, C. J. (2004). *An Introduction to Database Systems*. Addison-Wesley.<br>• SQLZoo Tutorial (`sqlzoo.net/wiki/Musicians`). |

---

## 📂 Contenido del Repositorio / Archivos de Entrega

* `lab01.pdf`: Documento principal con las respuestas, consultas SQL, álgebra/cálculo relacional y capturas.
* `musicians.astah`: Archivo de diseño con los diagramas de Casos de Uso, Lógico y Conceptos.
