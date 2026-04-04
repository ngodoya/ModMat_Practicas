# Modelación Matemática: Laboratorio de Prácticas

¡Bienvenido! Este repositorio es un compendio de implementaciones computacionales y análisis teóricos enfocados en la resolución de problemas mediante **modelación matemática**. El objetivo es documentar el proceso de aprendizaje y la aplicación de métodos numéricos en problemas de ingeniería.

---

## Tecnologías y Herramientas

Para el desarrollo de estas prácticas, se han empleado herramientas de código abierto y estándares de documentación técnica (esta materia la llevo de la mano con métodos numericos :p):

* **Lenguaje:** Python 3.13
* **Librerías Core:** * `NumPy`: Procesamiento de matrices y vectores fila.
    * `Matplotlib`: Visualización de datos y superficies 3D.
    * `SciPy`: Algoritmos avanzados de integración y optimización. (en proceso :v)
* **Entorno de Trabajo:** * **OS:** Linux (entorno de desarrollo principal).
    * **Notas:** Obsidian (integrado mediante Markdown y LaTeX).
    * **Control de Versiones:** Git + GitHub.

---

## Métodos Destacados

### 1. Resolución de EDOs
Implementación de métodos iterativos para sistemas dinámicos:
* **Método de Euler:** Aproximación lineal de primer orden.
* **Runge-Kutta (RK4):** Método de alta precisión para modelos físicos.

$$y_{n+1} = y_n + \frac{1}{6}(k_1 + 2k_2 + 2k_3 + k_4)h$$

### 2. Análisis Espacial y Superficies
Uso de visualización avanzada para el estudio de funciones multivariables, útil para fortalecer el **análisis de imagen** y la interpretación de datos complejos.

---

## Configuración en Linux

Si deseas replicar estos experimentos, puedes configurar tu entorno siguiendo estos comandos en la terminal:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/ngodoya/ModMat_Practicas.git
   cd ModMAT_PRACTICAS