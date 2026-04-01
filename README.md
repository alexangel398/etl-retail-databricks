# 🛒 ETL Pipeline — Online Retail con Databricks y PySpark

Pipeline ETL completo sobre datos reales de transacciones de e-commerce, desarrollado en Databricks usando PySpark y Delta Tables.

---

## 📌 Descripción del proyecto

Este proyecto implementa un pipeline ETL (Extract, Transform, Load) sobre el dataset público **Online Retail UCI**, que contiene 541.909 transacciones reales de una tienda mayorista del Reino Unido (2010–2011).

El pipeline limpia los datos crudos y genera dos reportes de negocio:
- Revenue total, facturas y clientes únicos **por país**
- Top 20 **productos más vendidos** por ingresos

---

## 🗂️ Estructura del repositorio
```
etl-retail-databricks/
├── pipeline_ventas_retail.py
└── README.md
```

## 🛠️ Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| Python 3 | Lenguaje principal |
| PySpark | Procesamiento distribuido de datos |
| Databricks | Plataforma de ejecución (Community Edition) |
| Delta Tables | Formato de almacenamiento de resultados |
| Git / GitHub | Control de versiones |

---

## 📊 Dataset

- **Fuente:** UCI Machine Learning Repository
- **Registros originales:** 541.909 transacciones
- **Registros después de limpieza:** ~397.924
- **Período:** Diciembre 2010 – Diciembre 2011

---

## 📈 Resultados obtenidos

**Top 5 países por revenue:**

| País | Revenue (£) | Facturas | Clientes |
|---|---|---|---|
| United Kingdom | 7.308.391 | 16.646 | 3.920 |
| Netherlands | 285.446 | 94 | 9 |
| EIRE | 265.545 | 260 | 3 |
| Germany | 228.867 | 457 | 94 |
| France | 209.024 | 389 | 87 |

**Top 5 productos por revenue:**

| Producto | Unidades | Revenue (£) |
|---|---|---|
| PAPER CRAFT LITTLE BIRDIE | 80.995 | 168.469 |
| REGENCY CAKESTAND 3 TIER | 12.402 | 142.592 |
| WHITE HANGING HEART T-LIGHT | 36.725 | 100.448 |
| JUMBO BAG RED RETROSPOT | 46.181 | 85.220 |
| MEDIUM CERAMIC TOP STORAGE JAR | 77.916 | 81.416 |

