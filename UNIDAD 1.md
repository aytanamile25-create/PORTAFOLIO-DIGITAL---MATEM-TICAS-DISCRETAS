<div align="center">

<img width="500" height="161" alt="image" src="https://github.com/user-attachments/assets/c8160560-6f3e-4419-b127-aaff91baab7a" />


# UNIVERSIDAD NACIONAL DE LOJA
## FACULTAD DE LA ENERGÍA, LAS INDUSTRIAS Y LOS RECURSOS NATURALES NO RENOVABLES
### CARRERA DE COMPUTACIÓN
**UNIDAD 1**
## 📑 Contenido de la Unidad 1

* [1. Lógica Proposicional](#1-lógica-proposicional)
* [2. Conectores Lógicos](#2-conectores-lógicos)
* [3. Tablas de Verdad](#3-tablas-de-verdad)
* [4. Leyes proposicionales](#4-leyes-proposicionales)
* [5. Leyes de inferencia](#leyes-de-inferencia)
* [6. Ejercicios resueltos](#ejercicios-resueltos)
* [7. Ejercicio aplicado](#ejercicio-aplicado)
* [8. Reflexión personal](#reflexión-personal)
* [9. Conclusión](#conclusión)
* [10. Anexos - Actividades Prácticas Experimentales](#anexos-actividades-prácticas-experimentales)

---
## RESUMEN TEÓRICO
---
## 1. Lógica Proposicional
La Lógica Proposicional es la rama de la lógica que estudia las proposiciones y las formas en que se combinan mediante conectores. Son  enunciados declarativos del cual se puede afirmar que es Verdadero (V) o Falso (F), sin emabrgo no puede ser ambos a la vez.
Ejemplo:
Proposiciones Simples: No tienen conectores: "Hoy es Viernes".

Proposiciones Compuestas: Unión de dos o más proposiciones simples mediante conectores: "Hoy es Viernes y tengo clase"
Conector que une a las proposiciones ( y ).

---

## 2. Conectores Lógicos
Símbolos que vinculan  distintas partes de una oración o texto.  Permiten transformar problemas de lenguaje natural en soluciones.
### 📑 Tabla de Operadores y Conectores Lógicos

| Operación | Conector | Símbolo | Significado | Ejemplo |
| :--- | :--- | :---: | :--- | :--- |
| **Negación** | No | $\neg$ | Cambia el valor de verdad | $\neg p$ |
| **Conjunción** | Y | $\land$ | Es verdadera solo si ambos son V | $p \land q$ |
| **Disyunción** | O | $\lor$ | Es falsa solo si ambos son F | $p \lor q$ |
| **Condicional** | Si... entonces | $\to$ | Solo es falsa si V implica F | $p \to q$ |
| **Bicondicional** | Si y solo si | $\leftrightarrow$ | Verdadera si ambos son iguales | $p \leftrightarrow q$ |
| **Disyunción Exclusiva** | O... o | $\oplus$ | Verdadera si solo uno es V | $p \oplus q$ |

---

## 3. Tablas de Verdad
Herramienta gráfica que permite determinar el valor de verdad de una proposición compuesta para todas las combinaciones posibles de sus variables.

Tautología: Todos los resultados finales son Verdaderos.

Contradicción: Todos los resultados finales son Falsos.

Contingencia: Los resultados finales están mezclados entre Verdaderos y Falsos.

---

## 4. Leyes proposicionales
Son principios fundamentales que permiten transformar y simplificar expresiones lógicas complejas en otras más sencillas que tienen el mismo valor de verdad.

### ⚖️ Leyes de la Equivalencia Lógica

| Nombre de la Ley | Expresión Lógica |
| :--- | :--- |
| **Ley de Idempotencia** | $p \lor p \equiv p$ <br> $p \land p \equiv p$ |
| **Ley Conmutativa** | $p \lor q \equiv q \lor p$ <br> $p \land q \equiv q \land p$ |
| **Ley Asociativa** | $(p \lor q) \lor r \equiv p \lor (q \lor r)$ <br> $(p \land q) \land r \equiv p \land (q \land r)$ |
| **Ley Distributiva** | $p \lor (q \land r) \equiv (p \lor q) \land (p \lor r)$ <br> $p \land (q \lor r) \equiv (p \land q) \lor (p \land r)$ |
| **Leyes de Identidad** | $p \lor F \equiv p$ <br> $p \land V \equiv p$ |
| **Leyes de Dominación** | $p \lor V \equiv V$ <br> $p \land F \equiv F$ |
| **Ley de Doble Negación** | $\neg(\neg p) \equiv p$ |
| **Leyes de De Morgan** | $\neg(p \land q) \equiv \neg p \lor \neg q$ <br> $\neg(p \lor q) \equiv \neg p \land \neg q$ |
| **Leyes de Absorción** | $p \lor (p \land q) \equiv p$ <br> $p \land (p \lor q) \equiv p$ |
| **Leyes del Complemento** | $p \lor \neg p \equiv V$ <br> $p \land \neg p \equiv F$ |
 

## 5. Leyes de inferencia 

Son esquemas de razonamiento deductivo que permite obtener una conclusión a partir de una o varias premisas.
Los mas comunes son:

Ley de De Morgan: $\neg(\neg p) \land \neg q$

Ley de Doble Negación: $p \land \neg q$
---
## 6. Ejercicios resueltos
<p align="left">
  <a href="./EJERCICIOS%20RESUELTOS.md">
    <img src="https://img.shields.io/badge/🚀%20ACCEDER%20A%20LA%20UNIDAD%201-CLICK%20AQUÍ-blueviolet?style=for-the-badge" />
  </a>
</p>

## 7. Ejercicio aplicado
**Planteamiento del problema**
"Para ingresar al laboratorio de computación en la noche, es necesario que seas estudiante de la carrera y que presentes tu carnet. Si no presentas tu carnet o no eres estudiante, entonces no podrás ingresar".
**Definición de proposiciones**
 p: Es estudiante de la carrera.
 
 q: Presenta el carnet.

 r: Puede ingresar al laboratorio.

 **Expresión simbólicaEl enunciado se puede formalizar de la siguiente manera**
 $$((p \land q) \to r) \land ((\neg p \lor \neg q) \to \neg r)$$

 **Análisis con Tabla de Verdad** 
 Si cumple ambos requisitos, puede entrar $(p \land q) \to r$.

| p | q | r | $p \land q$ | $(p \land q) \to r$ |
| :---: | :---: | :---: | :---: | :---: |
| V | V | V | V | **V** |
| V | V | F | V | **F** |
| V | F | V | F | **V** |
| F | V | V | F | **V** |

**Conclusión**

El análisis lógico demuestra que el reglamento es válido. Solo existe un error, cuando el estudiante cumple todo y el sistema no lo deja entrar.

---
## 8. Reflexión personal
**¿Qué fue lo más difícil de entender?**

En lo personal, se me complico un poco el tema de las leyes de inferencias lógicas, fue un tema bastante nuevo, no habia resuelto ejercicios con esos tipos de estructuras, sin embargo con investigación del tema, las leyes, y la práctica dentro del aula pude entender el tema, desarrollar con mas eficiencia los ejercicios y tener el conocimiento de la lógica relacionada con la computación.


**¿Qué tema comprendí mejor?**

Me parecio super chevere y sencillo, las tablas de verdad, las leyes de proposición, es facil comprender cuando se tiene claro cada ley, tambien me resulto mejor y fácil comprender porqur son lógicas matemáticas, cuando se analiza con atención cada ejercicio podemos llegar rapido a la respuesta. 


**¿Cómo puedo aplicar la lógica en mi carrera?**

La lógica dentro de la carrera de computación es la base para todo, se aplica de multiformes maneras, no solo es teoría sino también la creación de software que tengan un funcionamiento eficaz. La lógica se puede aplicar al crear aplicaciones de inteligencia artificial, software, programas o herramientas que facilitan al ser humnano en la vida cotidiana.

----

## 9. Conclusión
En conclusión durante la unidad aprendi nuevos temas, bases fundamentales dentro de la computación, ayuda a introduccirnos desde primer ciclo al desarrollo de software. Durante la unidad la teoría y practica que se llevaba a cabdo en cada clase fue muy buena y didáctica ya que fomenta la capacidad de dominar los temas con eficacia. La lógica computacional es muy importante y básica para realizar cualquier trabajo desde un pc hasta la creación de programas. Para llegar a comprender la lógica fue importante ver los subtemas que abarca la logica computacional que son los conectores lógicos, tablas de verdad, leyes de infernecia y proposicionales.
---
## 10.  Anexos - Actividades Prácticas Experimentales


