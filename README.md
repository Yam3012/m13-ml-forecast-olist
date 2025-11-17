#  Proyecto de Forecasting de Demanda – Olist
**Módulo Final – Inteligencia Artificial Aplicada**  
**Equipo:** Yamil Gamarra · Marianela Loza Rios · Enrique Yupanqui
##  Descripción del Proyecto
Este proyecto implementa un sistema de pronóstico de demanda mensual por categoría de producto utilizando el dataset Brasileño Olist. El objetivo es construir un modelo que prediga la cantidad de órdenes del siguiente mes para apoyar decisiones de inventario.
##  Target del Proyecto
Variable objetivo:
```
demand_next_month
```
##  División Temporal
- Total: 201610 → 201808 (23 meses)
- Train/Val: 19 meses
- Backtest: 201805–201807
- Prueba final docente: 201808
  
## Estructura
m13-ml-forecast-olist/
│
├── notebooks/
│   ├── Sprint1/
│   ├── Sprint2/
│   └── Sprint3/
│
├── src/
│   ├── ingesta/
│   ├── cleaning/
│   ├── features/
│   ├── models/
│   └── utils/
│
├── reports/
│   ├── sprint1.md
│   ├── sprint2.md
│   └── sprint3.md
│
├── README.md
├── requirements.txt
└── .gitignore


## Tecnologías
Python, Pandas, NumPy, Sklearn, XGBoost, CatBoost, Colab, Git, GitHub, Matplotlib, Seaborn, Google Colab, gitFlow 

## Flujo GitFlow
Ramas:
- yamil-dev
- marianela-dev
- enrique-dev
## Sprints
### Sprint 1
EDA, target, demand, reglas temporales.
### Sprint 2
Features (100+), baseline, KPIs, backtesting.
### Sprint 3
Modelos finales, dashboard, conclusiones.

## Métricas Técnicas
MAE, RMSE, MAPE, sMAPE, R².

## Métricas de Negocio
Pareto, correlación, ANOVA, Chi-cuadrado.

## Instalación
```
git clone https://github.com/<user>/m13-ml-forecast-olist.git
cd ml-forecast-olist
pip install -r requirements.txt
```

## Licencia
MIT License.
