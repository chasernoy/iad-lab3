# iad-lab3
# Лабораторная работа №3 «Снижение размерности данных»

## Данные
Файл: `data/extreme_pollution.csv`

## Структура репозитория
- `notebooks/lab3_pca.ipynb` — основной ноутбук с анализом (PCA, t‑SNE, UMAP).
- `data/` — папка с исходным датасетом.

## Запуск

### 1) Клонирование репозитория
git clone https://github.com/chasernoy/iad-lab3.git
cd iad-lab3

### 2) Окружение и зависимости
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter umap-learn

### 3) Запуск ноутбука
python3 -m jupyter lab
