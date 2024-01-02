# Actividad de Calidad.

## Introducción
- Link: https://github.com/estadistica-proyectos/calidad.git
- Integrantes del grupo: Alejandro Martínez; Claudia López; Frank Llonch; María González.

## Repositorio
La carpeta `data` con un archivo *csv* dónde se encuentran los correspondientes datos del ejercicio.

La carpeta `graphs` contiene archivos en formato png con los gráficos generados por el programa.

El archivo `main.ipynb` contiene un Jupyter Notebook programado en Python para el cálculo de las medidas pedidas en el ejercicio de calidad. A continuación, se proporciona una descripción y las librerías utilizadas en el código:

#### **Descripción**
El programa tiene como objetivo el cálculo de las distintas medidas de forma, dispersión, centralización, etc; para poder realizar un control de calidad.

#### **Librerías Utilizadas**
El código hace uso de las siguientes librerías de Python:

- `numpy`: Funciones para realizar operaciones numéricas eficientes.
- `matplotlib.pyplot`: Se emplea para la generación de gráficos y visualización de datos.
- `csv`: Lectura y creación de archivos CSV, facilitando la manipulación de datos tabulares en formato CSV.
- `statistics`: Funciones para realizar cálculos estadísticos básicos.
- `scipy.stats`: Funciones estadísticas, como cálculos de sesgo, curtosis y otras distribuciones estadísticas.
- `math`: Funciones matemáticas estándar para operaciones matemáticas avanzadas.

Se deben de tener estas librerías instaladas antes de ejecutar el código. Se indica como instalarlas en caso de no tenerlas.

## Enunciado
Con los datos de la siguiente tabla, <br>
1.15 1.20 1.17 1.16 1.16 1.15 1.17 1.20 1.16 1.19 1.17 1.13 1.15 1.20 1.18 1.17 1.16 1.20 1.17 1.17 1.20 1.14 1.19 1.13 1.19 1.16 1.18 1.16 1.17 1.15 1.21 1.15 1.20 1.18 1.17 1.17 1.13 1.16 1.16 1.17 1.20 1.18 1.15 1.13 1.20 1.17 1.19 1.23 1.20 1.24 1.17 1.17 1.17 1.17 1.18 1.24 1.16 1.18 1.16 1.22 1.23 1.22 1.19 1.13 1.15 1.15 1.22 1.19 1.18 1.19 1.17 1.16 1.17 1.18 1.19 1.23 1.19 1.16 1.19 1.20 1.17 1.13 1.22 1.19 1.21 1.20 1.19 1.17 1.19 1.22 1.19 1.18 1.11 1.19 1.19 1.17 1.19 1.17 1.20 1.16 1.19 1.20 1.20 1.17 1.25 1.16 1.16 1.20 1.20 1.16 1.18 1.21 1.20 1.22 1.19 1.14 1.19 1.17 1.20 1.16 1.15 1.20 1.12 1.11 1.18
<br>
Obtener:

En un proceso de inyección de plástico una característica de calidad del producto (disco) es su grosor, que debe ser de 1.20 mm con una tolerancia de ± 0.10 mm. Así, para considerar que el proceso de inyección fue satisfactorio, el grosor del disco debe estar entre la especificación inferior, EI = 1.10 y la superior, ES = 1.30.

En un estudio de capacidad para este proceso es necesario contestar las siguientes interrogantes: ¿qué tipo de discos en cuanto a grosor se están produciendo? ¿El grosor medio es adecuado? ¿La variabilidad del grosor es mucha o poca?

Para contestar estas preguntas, durante una semana se obtuvieron de una línea de producción los 125 datos de la tabla. El muestreo fue sistemático: cada determinado tiempo se tomaban cinco productos y se medían y al final de la semana se tuvieron los datos referidos.
- Media muestral.
-Mediana. Cuartiles.
- Moda.
- Desviación estándar muestral
- Coeficiente de Variación.
- Histograma de frecuencias utilizando regla de Strugles.
- Sesgo y Curtosis estandarizados.
- Diagrama de cajas.
- Índices: Cp, Cpi, Cps, Cpk, K.

(tomar como media poblacional la media muestral)
