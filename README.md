**English** · [Español](README.es.md)

# Marcos García

Data analyst/Technical Consultant. I spend most of my time in SQL, Power BI, and increasingly Python.

What I actually care about: getting the metric definition right before anyone builds a
chart on top of it. Most "the dashboard is wrong" tickets are really "we never agreed
what an active customer is" tickets.

This profile is where I work in public — the project below is the one I'd walk a hiring
manager through.

---

### [turismo-rd](https://github.com/marcos-analytics/turismo-rd)

**Did four years of tourism growth actually change the Dominican sector, or is there just
more of the same?**

55 months of official monthly data, 135 source markets, pulled from government Excel files
that nobody had cleaned — two-level merged headers, the year written once per twelve rows.

Growth of **46.9%** in the trend changed the level but not the shape: September is still
**35% below trend**, every year. The US share fell from 59% to 54% and South America
absorbed it, not Europe. A SARIMAX forecasts next month at **3.9% MAPE**, a third better
than the seasonal-naive benchmark — and adding flight counts as a regressor makes it worse,
which I left in the writeup rather than quietly dropping.

Each finding ends in a decision and how you'd know it worked. The one weak result — a
six-cluster panel regression — is deliberately kept out of the headline table and labelled
as a hypothesis.

`Python` · `pandas` · `statsmodels` · STL · SARIMAX · fixed-effects OLS

---

### Working with

`SQL` (Postgres, T-SQL) · `Power BI` / DAX · `Python` (pandas, DuckDB) · `dbt` · `Excel`
— the honest ordering, strongest first.

### Currently learning

Python for analysis work I used to do in Excel. Progress is visible in commit history
rather than in a certificate — turismo-rd is where that shows.

### Elsewhere

- [LinkedIn](https://www.linkedin.com/in/marcos-garc%C3%ADa-4a5786245/)
