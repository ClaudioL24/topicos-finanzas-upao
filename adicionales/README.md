# Material adicional de consulta

Temas del CFA Level II que **no forman parte del sílabo** de Tópicos de Finanzas Avanzadas (ECON-421, 2026-2), reunidos aquí para quien quiera ir más allá. Nada de esta carpeta se evalúa ni tiene entrega.

Provienen de un diseño anterior del curso (2026-1) centrado en métodos cuantitativos, renta fija y derivados. Solo el primer tema tiene material completo (diapositivas, práctica y ejercicios); los demás se listan con sus lecturas del CFA y la práctica que se proponía, por si alguien quiere desarrollarlos por su cuenta o pedir orientación en horario de consulta.

## Con material disponible

| Carpeta | Tema | Lectura CFA L2 | Qué incluye |
|---|---|---|---|
| [`regresion_multiple/`](regresion_multiple/) | Regresión múltiple: fundamentos, supuestos e interpretación de coeficientes | Quantitative Methods: *Basics of Multiple Regression and Underlying Assumptions* | `teoria.pdf`, `practica.ipynb` (retorno del IGBVL sobre cobre y tipo de cambio, con datos del BCRP y Yahoo Finance), `ejercicios.ipynb` |

Conecta con el curso: la estimación del beta por MCO (semana 2) y los modelos de factores (semana 9) son regresiones; este material explica qué hay detrás de la tabla de `statsmodels`.

## Temas de lectura (sin material propio)

| Tema | Lectura CFA L2 | Práctica sugerida en Python | Relación con el curso |
|---|---|---|---|
| Evaluación del modelo y especificación errónea | *Evaluating Regression Model Fit and Interpreting Model Results*; *Model Misspecification* | ANOVA, $R^2$ ajustado, AIC/BIC; Breusch-Pagan, Durbin-Watson, VIF y errores estándar robustos | Diagnósticos de la regresión del beta (semana 2) |
| Series de tiempo | *Extensions of Multiple Regression*; *Time-Series Analysis* | Tendencias, AR/ARIMA, prueba ADF, estacionalidad, ARCH, pares por cointegración | Modelado de retornos y volatilidad |
| Machine learning y proyectos con big data | *Machine Learning*; *Big Data Projects* | LASSO/Ridge, árboles y random forest, k-means con scikit-learn | Selección de factores y clasificación de activos |
| Ingreso residual y empresas privadas | *Residual Income Valuation*; *Private Company Valuation* | Modelo de ingreso residual con datos contables; descuentos por iliquidez y control | Complementa los múltiplos y el DCF (semanas 3 a 5) |
| Bonos con opciones incorporadas | *The Arbitrage-Free Valuation Framework*; *Valuation and Analysis of Bonds with Embedded Options* | Árbol binomial de tasas, bono callable, OAS, duración y convexidad efectivas | Extiende la estructura temporal (semana 12) |
| Riesgo de crédito y CDS | *Credit Analysis Models*; *Credit Default Swaps* | Probabilidad de default con Merton, curvas de spreads, valorización de un CDS | Complementa riesgo país y escenarios (semana 14) |
| Forwards, futuros y swaps | *Pricing and Valuation of Forward Commitments* | Forward PEN/USD por paridad cubierta con datos del BCRP; swap de tasas | Extiende tipos de cambio y política monetaria (semanas 11 a 13) |
| Opciones y Black-Scholes-Merton | *Valuation of Contingent Claims* | BSM y griegas, gráficos de estrategias, Monte Carlo de precios | Tema nuevo, sin equivalente en el sílabo |
| Riesgo de mercado avanzado | *Measuring and Managing Market Risk* | Expected Shortfall, EWMA y GARCH, backtesting de VaR (Kupiec) | Extiende el VaR de la semana 10 |
| Backtesting y gestión activa | *Backtesting and Simulation*; *Analysis of Active Portfolio Management* | Backtest de una estrategia, ratio de información, paridad de riesgo | Extiende Markowitz y evaluación de desempeño (semanas 7 y 10) |

## Cómo usar este material

1. Mismo entorno del curso (`.venv` con `requirements.txt`); los notebooks usan `utils/` de la raíz del repositorio.
2. En Google Colab, la primera celda de cada práctica clona el repositorio y entra a la carpeta correcta.
3. Las dudas se atienden en horario de consulta o por Canvas; no se reciben entregas de esta carpeta.
