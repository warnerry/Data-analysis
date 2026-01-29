# Data-analysis — лабораторные работы

Набор лабораторных работ по анализу данных и машинному обучению (Python, Jupyter).

## Содержание
- [ЛР1 — Предобработка данных (movies.csv)](./lab1)
- [ЛР2 — Визуализация и связь признаков (clients2.csv)](./lab2)
- [ЛР3 — Регрессия: линейная и полиномиальная (regression.xlsx)](./lab3)
- [ЛР4 — Кластеризация: KMeans / Agglomerative / DBSCAN (ecommerce_fraud.csv)](./lab4)
- [ЛР5 — Классификация анемии (scikit-learn)](./lab5)

## Как запустить
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
