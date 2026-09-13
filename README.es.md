[English](README.md) · **Español**

# Marcos García

Analista de datos / Consultor técnico. Paso la mayor parte del tiempo en SQL, Power BI y
cada vez más en Python.

Lo que de verdad me importa: acordar la definición de la métrica antes de que alguien
monte un gráfico encima. La mayoría de los tickets de "el dashboard está mal" son en
realidad tickets de "nunca acordamos qué es un cliente activo".

Este perfil es donde trabajo en público — el proyecto de abajo es el que le explicaría a
alguien que me esté evaluando.

---

### [turismo-rd](https://github.com/marcos-analytics/turismo-rd)

**¿Cuatro años de crecimiento turístico cambiaron algo del sector dominicano, o
simplemente hay más de lo mismo?**

55 meses de datos oficiales mensuales, 135 mercados de origen, sacados de Excel
gubernamentales que nadie había limpiado: encabezados de dos niveles con celdas
combinadas y el año escrito una sola vez cada doce filas.

Un crecimiento de **46.9%** en la tendencia cambió el nivel pero no la forma: septiembre
sigue **35% por debajo de la tendencia**, todos los años. La cuota de Estados Unidos cayó
de 59% a 54% y la absorbió Sudamérica, no Europa. Un SARIMAX pronostica el mes siguiente
con **3.9% de MAPE**, un tercio mejor que la referencia estacional ingenua — y agregarle
el conteo de vuelos como regresor lo empeora, algo que dejé escrito en vez de borrarlo en
silencio.

Cada hallazgo termina en una decisión y en cómo se sabría si funcionó. El único resultado
flojo —una regresión de panel con seis clusters— queda fuera de la tabla de titulares a
propósito y etiquetado como hipótesis.

`Python` · `pandas` · `statsmodels` · STL · SARIMAX · OLS con efectos fijos

---

### Trabajo con

`SQL` (Postgres, T-SQL) · `Power BI` / DAX · `Python` (pandas, DuckDB) · `dbt` · `Excel`
— en orden honesto, lo más fuerte primero.

### Aprendiendo ahora

Python para el trabajo de análisis que antes hacía en Excel. El avance se ve en el
historial de commits, no en un certificado — turismo-rd es donde se nota.

### En otros sitios

- LinkedIn — [linkedin.com/in/marcos-garcía-4a5786245](https://www.linkedin.com/in/marcos-garc%C3%ADa-4a5786245/)
