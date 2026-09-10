# ACTIVIDAD-6-TALLER-PR-CTICO-DE-REPASO-Y-CONSOLIDACI-N-PROGRAMACION-

## Datos Institucionales y Academicos
* Institucion: Escuela de Educacion Secundaria Tecnica N 1 (EEST N 1) "Eduardo Ader" - Vicente Lopez
* Materia: Laboratorio de Programacion (LPR)
* Curso / Año: 5.3 Año | Grupos A-B
* Ciclo Lectivo: 2026
* Actividad: ACTIVIDAD-6 - Suite de Taller de Repaso e Integracion (ACT06 [P3_HQI_2.0])

---

## Integrantes del Equipo (P.I.A)
* Sofia Mojica: Desarrollo del Reto 1 (Cuestionario Tecnico y Caso Base de Recursividad) y documentacion en Informe PDF.
* Gabriel Zacarias: Implementacion del Reto 2 (Busqueda en Arreglos y Optimizacion con break).
* Mateo Roberts: Desarrollo del Reto 3 (Verificacion de Direccionamiento de Memoria en RAM con el operador &).
* Leonel De Armas: Algoritmo de Intercambio de Valores con Punteros y estructuracion modular de src/main.cpp.

---

## Descripcion del Proyecto
Este repositorio contiene la resolucion integral en C++ de la suite de ejercicios y retos tecnicos del taller de laboratorio. Su objetivo principal es reforzar y evaluar conceptos clave a bajo nivel como:
* Control de flujo y optimizacion de procesamiento en CPU.
* Gestion de memoria RAM, Call Stack y prevencion de Stack Overflow.
* Aritmetica de punteros y comprobacion de celdas contiguas de memoria.
* Intercambio de valores (swap) mediante paso por referencia y variables temporales.

---

## Menu de Retos / Modulos de la Suite

El programa principal (src/main.cpp) ejecuta de forma modular una interfaz interactiva por consola con los siguientes componentes:

1. Reto 1: Caso Base y Recursividad
   Demostracion teorica y simulada del comportamiento de las llamadas recursivas sobre la pila de llamadas (Call Stack) y el desbordamiento de memoria por falta de condicion de corte.

2. Reto 2: Busqueda Eficiente en Arreglos (break)
   Algoritmo de busqueda que optimiza la cantidad de ciclos de reloj del microprocesador interrumpiendo el bucle apenas se encuentra el elemento buscado.

3. Reto 3: Inspeccion de Direccionamiento de Memoria RAM
   Uso explicito del operador de direccion (&) para verificar la contiguedad fisica en la memoria de los elementos de un array de datos.

4. Reto 4: Intercambio de Valores con Punteros (swap)
   Implementacion de algoritmos de manipulacion directa de celdas de memoria usando punteros y variables temporales de resguardo.

5. Reto 5: Informe y Autoevaluacion
   Sintesis de analisis conceptual y autoevaluacion tecnica del equipo sobre los aspectos de menor nivel abordados en la practica.

---

## Estructura del Repositorio

REPASOGENERAL/
|-- .gitignore
|-- LICENSE
|-- README.md
|-- Docs/
|   `-- EEST1_LPR2026_ACT06_[P3_HQI_2.0]_Informe_v1.0.0.pdf
|-- CHANGELOG.md
|-- src/
|   `-- main.cpp
`-- Capturas/
    |-- ejecucion_repaso.png
    `-- traza_memoria.png

---

## Instrucciones de Compilacion y Ejecucion

Para compilar y ejecutar la suite localmente desde una terminal con g++:

1. Clonar el repositorio:
   git clone https://github.com/tu-usuario/ACTIVIDAD-6-TALLER-PR-CTICO-DE-REPASO-Y-CONSOLIDACI-N-PROGRAMACION.git

2. Navegar al directorio del proyecto:
   cd ACTIVIDAD-6-TALLER-PR-CTICO-DE-REPASO-Y-CONSOLIDACI-N-PROGRAMACION/REPASOGENERAL

3. Compilar el codigo fuente en C++:
   g++ -std=c++17 src/main.cpp -o main.exe

4. Ejecutar el programa:
   ./main.exe

---

## Licencia
Este proyecto se distribuye bajo la licencia MIT. Para mas informacion, consultar el archivo LICENSE.
