# Создаем виртуальное окружение (оно будет храниться в папке 'venv')
python3 -m venv venv

# Активируем окружение (в начале строки появится приписка (venv))
source venv/bin/activate

# Обновляем pip (на всякий случай)
pip install --upgrade pip

# Ставим JupyterLab и все библиотеки, которые нужны для твоего ноутбука
pip install jupyterlab pandas numpy matplotlib seaborn scikit-learn

# А теперь запускаем сам JupyterLab!
jupyter lab










гитигнор:



# ==========================================
# Python, Data Science & Jupyter
# ==========================================

# Виртуальные окружения (обязательно!)
venv/
env/
.venv/
ENV/

# Байт-код Python и кэш
__pycache__/
*.py[cod]
*$py.class
*.so

# Скрытые папки Jupyter (создаются автоматически при сохранении ноутбука)
.ipynb_checkpoints/

# Настройки редакторов кода
.vscode/
.idea/
*.swp
*.swo
*~

# Системный мусор (macOS / Windows)
.DS_Store
Thumbs.db

# ==========================================
# Большие файлы с данными (Опционально)
# ==========================================
# В ML-проектах датасеты часто весят десятки мегабайт.
# Git не любит большие файлы. Если твой train.json тяжелый, 
# раскомментируй (убери #) следующие строки, чтобы не пушить его в репозиторий:
# data/
# *.csv
# *.json
# *.parquet
.ipynb_checkpoints/