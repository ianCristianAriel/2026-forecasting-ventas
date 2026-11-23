## 1. Contexto del negocio

Rossmann es una cadena de farmacias y tiendas minoristas que necesita tomar decisiones estratégicas sobre la inversión destinada a la renovación de sus establecimientos. Para ello, el director financiero (CFO) requiere estimaciones confiables de los ingresos futuros de cada tienda.

## 2. Problema de negocio

La empresa necesita anticipar el comportamiento de sus ventas para planificar la asignación del presupuesto de renovación de sus tiendas. La falta de estimaciones precisas dificulta la evaluación del potencial de ingresos de cada establecimiento y la toma de decisiones de inversión.

## 3. Business Objective

Desarrollar un modelo de predicción de ventas diarias por tienda para las próximas seis semanas, con el fin de proporcionar al director financiero información confiable que le permita planificar y optimizar la asignación del presupuesto destinado a la renovación de los establecimientos. Al mismo tiempo que comprender posibles factores que influencien dicho aumento o baja en la demanda.

## 4. Objetivo de Data Science

Construir un modelo de regresión supervisada que, utilizando información histórica de ventas, características de las tiendas y variables temporales y promocionales, permita estimar las ventas futuras de cada establecimiento. Al mismo tiempo que se desarrollara un modelo supervisado de clasificación sobre la target discretizada en cuartiles, con la intención de comprender los factores involucrados en diferentes rangos de ventas.

La variable objetivo será Sales, y las predicciones se realizarán para cada combinación de tienda (Store) y fecha (Date).

## 5. Criterio de éxito del negocio

El proyecto será exitoso si las predicciones permiten mejorar la planificación financiera y contribuir a una asignación más eficiente del presupuesto de renovación, proporcionando información útil para la toma de decisiones estratégicas.

## 6. Criterio de éxito analítico

El modelo deberá generar predicciones de ventas con un error suficientemente bajo para que puedan utilizarse como insumo en la planificación financiera.

Se utilizará el MAPE (Error Porcentual Absoluto Medio) como métrica de evaluación, buscando minimizar la diferencia entre las ventas reales y las predichas.
