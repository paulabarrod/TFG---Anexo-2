# Métodos multivariantes para el análisis de datos cualitativos y mixtos: un enfoque de agrupamiento y clasificación

Este repositorio contiene el Anexo 2 del Trabajo de Fin de Grado en Estadística de la Universidad de Salamanca.

Su objetivo principal es mostrar el código fuente en Python del caso práctico realizado a partir de la revisión bibliográfica de las técnicas de agrupamiento y clasficación, que se basa en el análisis de los estudiantes finladeses en el estudio de PISA 2022.

Debido al gran volumen de la base de datos no se incluye el conjunto de datos orginal. No obstante, el análisis se realizó empleando el cuestionario oficial de los alumnos del estudio de PISA 2022 que se encuentra disponible en el portal OECD: https://www.oecd.org/

## Objetivos del Caso Práctico
Este caso práctico tiene como objetivo principal la clasificación de estudiantes finlandeses similares según el estudio PISA 2022. Se consideran los siguientes objetivos secundarios:

	1. Identificación de grupos similares no establecidos por PISA 2022 mediante técnicas de agrupamiento.
	2. Analizar los factores que ocasionan la división a través de métodos de clasificación.

## Estructura del Código
El cuaderno de Jupyter se estructura con el siguiente orden meteodológico:

	1. Carga y preparación de la base de datos: se importa el conjunto de datos oficial de la OECD.
	2. Descripción de la muestra: se tratan los valores faltantes y se decribe el comportamiento univariante y multivariante de las variables.
	3. Resultados: Primero, se idetifica la clasificación de los alumnos y después se interpretan los factors asociados a la clasificación.

## Requisitos
Para ejectuar este cuaderno se necesitan las siguientes librerías:
```bash
pip install numpy pandas pyreadstat matplotlib seaborn scipy gower scikit-learn kmedoids  kmodes pillow

```

