# Business Objective – Rossmann Sales

## 1. Contexto del negocio

Rossmann es una cadena de farmacias y tiendas minoristas que necesita tomar decisiones estratégicas sobre la inversión destinada a la renovación de sus establecimientos. Para ello, el director financiero (CFO) requiere estimaciones confiables de los ingresos futuros de cada tienda.

## 2. Problema de negocio

La empresa necesita anticipar el comportamiento de sus ventas para planificar la asignación del presupuesto destinado a la renovación de sus establecimientos.

La falta de estimaciones precisas sobre las ventas futuras dificulta la evaluación del potencial de ingresos de cada tienda y limita la capacidad de la empresa para tomar decisiones de inversión fundamentadas en información cuantitativa.

## 3. Business Objective

Desarrollar un modelo de predicción de ventas diarias por tienda para las próximas seis semanas, con el fin de proporcionar al director financiero estimaciones confiables de los ingresos futuros que permitan mejorar la planificación financiera y optimizar la asignación del presupuesto destinado a la renovación de los establecimientos.

## 4. Objetivo de Data Science

Construir un modelo de regresión supervisada que, utilizando información histórica de ventas, características de las tiendas y variables temporales y promocionales, permita estimar las ventas futuras de cada establecimiento para un horizonte de seis semanas.

La variable objetivo será Sales, y las predicciones se realizarán para cada combinación de tienda (Store) y fecha (Date).

El modelo deberá capturar los patrones temporales presentes en los datos históricos y utilizar las variables disponibles para generar estimaciones precisas de las ventas futuras.

## 5. Criterio de éxito del negocio

El proyecto será exitoso si las predicciones de ventas proporcionan información confiable y útil para la planificación financiera de Rossmann, contribuyendo a una asignación más eficiente del presupuesto de renovación de sus establecimientos.

Las estimaciones deberán permitir comparar el potencial de ingresos futuros de las distintas tiendas y servir como insumo para la toma de decisiones estratégicas de inversión.

## 6. Criterio de éxito analítico

El modelo deberá generar predicciones de ventas con un nivel de error suficientemente bajo para que puedan utilizarse como insumo en la planificación financiera.

Se utilizará el MAPE (Error Porcentual Absoluto Medio) como métrica principal de evaluación, buscando minimizar la diferencia porcentual entre las ventas reales y las predichas.

El desempeño del modelo se evaluará sobre un conjunto de datos de prueba que represente un período posterior al utilizado para el entrenamiento, con el objetivo de medir su capacidad para predecir ventas futuras en condiciones similares a las de una implementación real.