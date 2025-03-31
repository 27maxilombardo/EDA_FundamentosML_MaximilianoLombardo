# EDA_FundamentosML_MaximilianoLombardo
# Análisis de Rotación de Personal (Attrition)

Este repositorio contiene un análisis exploratorio de datos sobre la rotación de personal (attrition) en una empresa, utilizando un dataset de IBM HR Analytics. 

## Objetivo

El objetivo principal de este análisis es explorar los factores que podrían estar asociados a la rotación de personal y describir el perfil de los empleados que tienden a quedarse o a abandonar la empresa.

## Dataset

El dataset utilizado se llama "IBM HR Analytics Employee Attrition & Performance" y está disponible en Kaggle. Contiene información sobre empleados de una empresa, incluyendo datos demográficos, laborales y de satisfacción.

## Análisis realizado

El análisis se realiza utilizando Python y las bibliotecas Pandas, Matplotlib y Seaborn. Se exploran las siguientes variables:

- **Attrition:** Variable objetivo que indica si el empleado abandonó la empresa (Yes) o no (No).
- **MonthlyIncome:** Ingreso mensual del empleado.
- **Age:** Edad del empleado.
- **TotalWorkingYears:** Años totales de experiencia laboral del empleado.
- **JobSatisfaction:** Nivel de satisfacción laboral del empleado.
- **JobRole:** Cargo del empleado.
- **Education:** Nivel de educación del empleado.

Se realizan los siguientes análisis:

- **Análisis descriptivo:** Se calculan estadísticas descriptivas para las variables numéricas, se observan las distribuciones de las variables y se identifican valores atípicos.
- **Análisis de correlación:** Se explora la relación entre la variable "Attrition" y otras variables, tanto numéricas como categóricas, utilizando gráficos de dispersión, boxplots, tablas de contingencia y gráficos de barras.
- **Descripción de perfiles:** Se describe el perfil de los empleados que tienden a quedarse y los que tienden a abandonar la empresa, basándose en los resultados de los análisis anteriores.

## Conclusiones

Las conclusiones del análisis se detallan en el notebook. Se identifican algunos factores que podrían estar asociados a la rotación de personal, como la satisfacción laboral, el nivel de ingreso y la antigüedad en la empresa. También se describen las características de los empleados que
