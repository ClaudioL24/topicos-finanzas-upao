# Adicional: regresión múltiple, fundamentos y supuestos

**Material de consulta, no evaluado.** Tema de Quantitative Methods del CFA Level II (*Basics of Multiple Regression and Underlying Assumptions*) que no está en el sílabo del curso.

## Objetivos

- Formular un modelo de regresión múltiple y describir su uso en el análisis financiero.
- Enunciar los supuestos del modelo clásico.
- Interpretar los coeficientes estimados (*holding all other independent variables constant*).

## Práctica en Python

Modelo de referencia con datos reales (retornos mensuales):

$$r_{IGBVL} = b_0 + b_1 \, r_{cobre} + b_2 \, \Delta TC + \varepsilon$$

- Descarga por API: cobre (Yahoo Finance, `HG=F`), tipo de cambio e índice bursátil (BCRPData, `utils/bcrp.py`).
- Estimación con `statsmodels` y lectura de la tabla de resultados.
- Primer diagnóstico visual: residuos contra valores ajustados.

## Archivos

| Archivo | Contenido |
|---|---|
| `teoria.pdf` | Diapositivas |
| `practica.ipynb` | Notebook guiado |
| `ejercicios.ipynb` | Ejercicios propuestos (replicar con otra acción minera, cuatro ítems tipo CFA) |

## Relación con el curso

La estimación del beta de la semana 2 y los modelos de factores de la semana 9 son regresiones; aquí se explica qué significa cada elemento de la salida de `statsmodels` y qué supuestos se están asumiendo.
