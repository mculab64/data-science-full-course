# 📘 Полный курс Data Science: от Python до веб-приложения

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=Jupyter)](https://jupyter.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> Учебное пособие **«Полный курс Data Science: от Python до веб-приложения»** — это комплексный курс, охватывающий весь путь специалиста по данным: от основ программирования на Python до развертывания готовых ML-моделей в виде веб-сервисов.

**Авторы:** С.Ю. Добдин, А.В. Скрипаль
**Издательство:** Лань, 2026
**ISBN:** 978-5-507-53863-8

---

## 📖 О курсе

Курс состоит из **двух частей**:

| Часть | Название | Описание |
|---|---|---|
| **Часть 1** | Теория и инструменты | Фундаментальные знания, методы и подходы Data Science с примерами кода |
| **Часть 2** | Инженерный практикум | Более 200 практических заданий для закрепления навыков |

**Целевая аудитория:** студенты, аспиранты и преподаватели инженерных и естественно-научных специальностей.

**Изучаемые дисциплины:**
- Искусственный интеллект и информационные технологии в медицине
- Нейросетевая инженерия
- Практикум по компьютерному моделированию

---

## 🚀 Быстрый старт

### 1. Клонирование репозитория

```bash
git clone https://github.com/your_username/data-science-full-course.git
cd data-science-full-course
```

### 2. Создание виртуального окружения

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Установка зависимостей

```bash
pip install -r requirements.txt
```

### 4. Запуск Jupyter Notebook

```bash
jupyter notebook
```

---

## 📂 Структура репозитория

```
data-science-full-course/
│
├── README.md                      # Этот файл
├── LICENSE                        # Лицензия MIT
├── requirements.txt               # Зависимости Python
├── .gitignore                     # Игнорируемые файлы
│
├── datasets/                      # Все датасеты курса
│   ├── iris.csv
│   ├── titanic.csv
│   ├── bank_churn.csv
│   ├── boston.csv
│   ├── wine.csv
│   ├── aep_hourly.csv
│   ├── temp_around.csv
│   ├── precious_metal.csv
│   ├── animals/                   # Изображения кошек и собак
│   └── haar_cascades/             # XML-каскады Хаара
│
├── part_1_theory/                 # Часть 1. Теория и инструменты
│   ├── README.md
│   ├── chapter_01_python/
│   ├── chapter_02_tools/
│   ├── chapter_03_preprocessing/
│   ├── chapter_04_visualization/
│   ├── chapter_05_statistics/
│   ├── chapter_06_eda/
│   ├── chapter_07_machine_learning/
│   ├── chapter_08_deep_learning/
│   ├── chapter_09_computer_vision/
│   ├── chapter_10_nlp/
│   ├── chapter_11_databases/
│   └── chapter_12_deployment/
│
└── part_2_practicum/              # Часть 2. Инженерный практикум
    ├── README.md
    ├── block_01_data_types/
    ├── block_02_tools/
    ├── block_03_preprocessing/
    ├── block_04_visualization/
    ├── block_05_statistics/
    ├── block_06_eda/
    ├── block_07_machine_learning/
    ├── block_08_deep_learning/
    ├── block_09_computer_vision/
    ├── block_10_nlp/
    ├── block_11_databases/
    └── block_12_capstone_project/
```

---

## 📚 Содержание курса

### 🧩 Часть 1. Теория и инструменты

<details>
<summary><b>Раздел 1. Язык программирования Python</b></summary>

**Что изучается:**
- Типы данных, условные операторы, циклы
- Коллекции: списки, кортежи, множества, словари
- Функции, области видимости, рекурсия, lambda
- Объектно-ориентированное программирование (ООП)
- Исключения, файловый ввод-вывод, модули и пакеты
- Итераторы, генераторы, декораторы

**Материалы:** [`part_1_theory/chapter_01_python/`](./part_1_theory/chapter_01_python/)
</details>

<details>
<summary><b>Раздел 2. Инструменты для работы в Data Science</b></summary>

**Что изучается:**
- Visual Studio Code — установка, расширения, работа с Python
- GigaIDE — отечественная среда разработки
- Jupyter Notebook и Google Colab
- Платформа Kaggle для соревнований по ML

**Материалы:** [`part_1_theory/chapter_02_tools/`](./part_1_theory/chapter_02_tools/)
</details>

<details>
<summary><b>Раздел 3. Предобработка и хранение данных</b></summary>

**Что изучается:**
- Библиотека NumPy для работы с массивами
- Библиотека Pandas для табличных данных
- Хранение данных: CSV, XLSX, JSON, TXT
- Парсинг HTML, работа с API
- Базы данных SQLite
- Система контроля версий Git, GitHub, GitVerse

**Материалы:** [`part_1_theory/chapter_03_preprocessing/`](./part_1_theory/chapter_03_preprocessing/)
</details>

<details>
<summary><b>Раздел 4. Визуализация данных</b></summary>

**Что изучается:**
- Виды графиков и правила их оформления
- Matplotlib — базовые и продвинутые графики
- Seaborn — статистическая визуализация
- Plotly — интерактивные графики

**Материалы:** [`part_1_theory/chapter_04_visualization/`](./part_1_theory/chapter_04_visualization/)
</details>

<details>
<summary><b>Раздел 5. Статистический анализ данных</b></summary>

**Что изучается:**
- Описательная статистика: меры положения, разброса, асимметрии
- Корреляция: Пирсон, Спирмен, Кендалл
- Статистические гипотезы, A/A и A/B тестирование
- P-value и доверительные интервалы
- Параметрические и непараметрические тесты
- Виды распределений и проверка на нормальность

**Материалы:** [`part_1_theory/chapter_05_statistics/`](./part_1_theory/chapter_05_statistics/)
</details>

<details>
<summary><b>Раздел 6. Очистка данных и EDA</b></summary>

**Что изучается:**
- Обработка пропущенных значений (импутация)
- Удаление и исправление выбросов
- Feature Engineering — создание новых признаков
- Кодирование категориальных признаков
- Feature Transformation: масштабирование, стандартизация, PCA
- Feature Selection — отбор значимых признаков

**Материалы:** [`part_1_theory/chapter_06_eda/`](./part_1_theory/chapter_06_eda/)
</details>

<details>
<summary><b>Раздел 7. Машинное обучение</b></summary>

**Что изучается:**
- Виды алгоритмов ML: с учителем, без учителя, с подкреплением
- Регрессия: линейная, полиномиальная, метрики (MAE, MSE, RMSE, R²)
- Классификация: логистическая регрессия, k-NN, деревья решений
- Метрики классификации: Accuracy, Precision, Recall, F1, ROC-AUC
- Кластеризация: k-means, иерархическая, DBSCAN
- Валидация и оптимизация гиперпараметров
- Ансамбли: бэггинг, стекинг, бустинг
- Пайплайны в ML

**Материалы:** [`part_1_theory/chapter_07_machine_learning/`](./part_1_theory/chapter_07_machine_learning/)
</details>

<details>
<summary><b>Раздел 8. Глубокое обучение</b></summary>

**Что изучается:**
- Модель искусственного нейрона и нейронные сети
- Фреймворк PyTorch и тензорное представление данных
- Конвейеры для пакетной обработки (Dataset, DataLoader)
- Линейная регрессия и классификация на нейросетях
- Свёрточные нейронные сети (CNN)
- Свёртка, объединение, автоградиент
- Рекуррентные сети (RNN, LSTM, GRU)
- Трансформеры и генеративно-состязательные сети (GAN)

**Материалы:** [`part_1_theory/chapter_08_deep_learning/`](./part_1_theory/chapter_08_deep_learning/)
</details>

<details>
<summary><b>Раздел 9. Компьютерное зрение (OpenCV)</b></summary>

**Что изучается:**
- Фильтрация и преобразование изображений
- Поиск объектов и измерение линейных размеров
- Трекинг объектов: MOG2, Meanshift, Camshift
- Детекторы признаков: Harris, SIFT, FAST, ORB
- Каскадные классификаторы Хаара
- Машинные алгоритмы для анализа изображений (HOG + SVM, YOLO)
- Работа с веб-камерой и видеопотоком

**Материалы:** [`part_1_theory/chapter_09_computer_vision/`](./part_1_theory/chapter_09_computer_vision/)
</details>

<details>
<summary><b>Раздел 10. Обработка естественного языка (NLP)</b></summary>

**Что изучается:**
- Кодирование данных: One-Hot, TF, TF-IDF, эмбеддинги
- Токенизация, лемматизация, стемминг
- Перенос обучения (Transfer Learning) и модели BERT, GPT
- Распознавание именованных сущностей (NER)
- Системы вопрос-ответ (QA)
- Машинный перевод

**Материалы:** [`part_1_theory/chapter_10_nlp/`](./part_1_theory/chapter_10_nlp/)
</details>

<details>
<summary><b>Раздел 11. Работа с базами данных (PostgreSQL)</b></summary>

**Что изучается:**
- Принципы построения реляционных баз данных
- Язык SQL: SELECT, WHERE, JOIN, GROUP BY, подзапросы, CTE
- СУБД PostgreSQL и утилита pgAdmin
- Клиенты для работы с БД: DBeaver, DbVisualizer
- Работа с PostgreSQL из Python (psycopg2, SQLAlchemy)

**Материалы:** [`part_1_theory/chapter_11_databases/`](./part_1_theory/chapter_11_databases/)
</details>

<details>
<summary><b>Раздел 12. Развертывание и мониторинг модели</b></summary>

**Что изучается:**
- Реализация ML-алгоритма для задачи классификации
- Создание фронтенда и бэкенда веб-приложения
- Фреймворки Flask и Django
- Контейнеризация с Docker и Docker Hub
- Развертывание на сервере с Ubuntu через SSH
- Трехуровневая архитектура: Nginx + Gunicorn + Uvicorn

**Материалы:** [`part_1_theory/chapter_12_deployment/`](./part_1_theory/chapter_12_deployment/)
</details>

---

### 🧪 Часть 2. Инженерный практикум

> **Более 200 заданий** разного уровня сложности — от базовых до продвинутых.

<details>
<summary><b>Блок 1. Практические задания по типам данных</b></summary>

Задания на работу с числами, строками, булевыми значениями, вводом-выводом.

**Материалы:** [`part_2_practicum/block_01_data_types/`](./part_2_practicum/block_01_data_types/)
</details>

<details>
<summary><b>Блок 2. Инструментарий разработчика Python</b></summary>

Настройка VS Code, GigaIDE, Jupyter Notebook, Google Colab, работа с Kaggle.

**Материалы:** [`part_2_practicum/block_02_tools/`](./part_2_practicum/block_02_tools/)
</details>

<details>
<summary><b>Блок 3. Предобработка и хранение данных</b></summary>

NumPy, Pandas, работа с файлами, парсинг HTML, API, SQLite, Git.

**Материалы:** [`part_2_practicum/block_03_preprocessing/`](./part_2_practicum/block_03_preprocessing/)
</details>

<details>
<summary><b>Блок 4. Визуализация данных</b></summary>

Графики в Matplotlib, Pandas, Seaborn. Настройка стилей.

**Материалы:** [`part_2_practicum/block_04_visualization/`](./part_2_practicum/block_04_visualization/)
</details>

<details>
<summary><b>Блок 5. Статистика и проверка гипотез</b></summary>

Описательная статистика, корреляция, доверительные интервалы, A/B-тесты.

**Материалы:** [`part_2_practicum/block_05_statistics/`](./part_2_practicum/block_05_statistics/)
</details>

<details>
<summary><b>Блок 6. Подготовка данных и Feature Engineering</b></summary>

Пропуски, выбросы, кодирование категорий, трансформация, PCA, отбор признаков.

**Материалы:** [`part_2_practicum/block_06_eda/`](./part_2_practicum/block_06_eda/)
</details>

<details>
<summary><b>Блок 7. Машинное обучение. Базовые алгоритмы</b></summary>

Регрессия, классификация, кластеризация, валидация, оптимизация, ансамбли, пайплайны.

**Материалы:** [`part_2_practicum/block_07_machine_learning/`](./part_2_practicum/block_07_machine_learning/)
</details>

<details>
<summary><b>Блок 8. Глубокое обучение (PyTorch)</b></summary>

Нейроны, тензоры, DataLoader, линейная регрессия, CNN, RNN, LSTM, GAN.

**Материалы:** [`part_2_practicum/block_08_deep_learning/`](./part_2_practicum/block_08_deep_learning/)
</details>

<details>
<summary><b>Блок 9. Компьютерное зрение (OpenCV)</b></summary>

Фильтрация, поиск объектов, трекинг, детекторы признаков, каскады Хаара, YOLO.

**Материалы:** [`part_2_practicum/block_09_computer_vision/`](./part_2_practicum/block_09_computer_vision/)
</details>

<details>
<summary><b>Блок 10. Обработка естественного языка (NLP)</b></summary>

Кодирование данных, токенизация, перенос обучения, NER, QA, машинный перевод.

**Материалы:** [`part_2_practicum/block_10_nlp/`](./part_2_practicum/block_10_nlp/)
</details>

<details>
<summary><b>Блок 11. Базы данных и SQL</b></summary>

Проектирование БД, SQL-запросы, JOIN, CTE, PostgreSQL, Python + БД.

**Материалы:** [`part_2_practicum/block_11_databases/`](./part_2_practicum/block_11_databases/)
</details>

<details>
<summary><b>Блок 12. Сквозной проект: от идеи до веб-сервиса</b></summary>

Полный цикл: EDA → ML-модель → Flask-приложение → Docker → развертывание.

**Материалы:** [`part_2_practicum/block_12_capstone_project/`](./part_2_practicum/block_12_capstone_project/)
</details>

---

## 📊 Используемые датасеты

Все датасеты находятся в папке [`datasets/`](./datasets/).

| Датасет | Описание | Используется в разделах |
|---|---|---|
| `iris.csv` | Размеры цветков ириса (3 класса) | 4, 6, 7, 8 |
| `titanic.csv` | Данные о пассажирах «Титаника» | 3, 5, 6, 7, 12 |
| `bank_churn.csv` | Данные об оттоке клиентов банка | 6, 7, 11, 12 |
| `boston.csv` | Цены на жилье в Бостоне | 5, 6, 7 |
| `wine.csv` | Химический состав вин (3 класса) | 6, 7, 8 |
| `aep_hourly.csv` | Почасовое потребление электроэнергии | 6, 8, 9 |
| `temp_around.csv` | Температура воздуха и земли | 7, 8 |
| `precious_metal.csv` | Цены на драгоценные металлы | 3, 6 |
| `animals/` | Изображения кошек и собак | 8, 9 |
| `haar_cascades/` | XML-каскады Хаара для OpenCV | 9 |

> **Примечание:** Все данные можно скачать из облачного хранилища по ссылке, указанной в книге: https://vk.cc/d0PF0e

---

## 🛠️ Используемые технологии и инструменты

### Языки и библиотеки

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.3+-013243?logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-3.0+-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.7+-F7931E?logo=scikit-learn)
![PyTorch](https://img.shields.io/badge/PyTorch-2.6+-EE4C2C?logo=pytorch)
![OpenCV](https://img.shields.io/badge/OpenCV-4.11+-5C3EE8?logo=opencv)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18-336791?logo=postgresql)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

### Среды разработки

- **Visual Studio Code** — основная IDE
- **GigaIDE** — отечественная среда разработки
- **Jupyter Notebook / JupyterLab**
- **Google Colab** — облачная среда
- **PyCharm** — альтернативная IDE
- **Kaggle Notebooks** — для соревнований

### Базы данных

- **SQLite** — встроенная БД
- **PostgreSQL** — основная СУБД курса
- **pgAdmin** — графическая утилита
- **DBeaver Community** — универсальный SQL-клиент

---

## 🎯 Компетенции после курса

После освоения курса вы будете **знать:**

- ✅ Основные инструменты математической обработки информации с применением Python
- ✅ Методы статистического анализа и визуализации данных
- ✅ Алгоритмы машинного обучения: регрессия, классификация, кластеризация
- ✅ Архитектуры глубоких нейронных сетей: CNN, RNN, LSTM, GAN
- ✅ Принципы работы с базами данных и языком SQL
- ✅ Методы развертывания ML-моделей в виде веб-приложений

Вы будете **уметь:**

- ✅ Выполнять исследовательский анализ данных (EDA)
- ✅ Создавать и обучать модели машинного обучения
- ✅ Применять глубокое обучение для задач компьютерного зрения и NLP
- ✅ Проектировать реляционные базы данных
- ✅ Развертывать модели с использованием Docker и облачных сервисов

Вы будете **владеть:**

- ✅ Навыками разработки алгоритмов машинного обучения
- ✅ Инструментами инженерии признаков и отбора значимых признаков
- ✅ Методами оптимизации гиперпараметров
- ✅ Технологиями контейнеризации и деплоймента

---

## 🤝 Как внести вклад

Мы приветствуем любые улучшения! Если вы нашли ошибку или хотите что-то дополнить:

1. Сделайте **Fork** репозитория
2. Создайте ветку для вашей функции: `git checkout -b feature/AmazingFeature`
3. Зафиксируйте изменения: `git commit -m 'Add some AmazingFeature'`
4. Отправьте изменения: `git push origin feature/AmazingFeature`
5. Откройте **Pull Request**

### Сообщения об ошибках

Если вы нашли ошибку в коде или тексте, создайте **Issue** с подробным описанием:
- Что вы делали
- Что ожидали получить
- Что получили на самом деле
- Ваша версия Python и библиотек

---

## 📄 Лицензия

Этот проект распространяется под лицензией **MIT**. Подробности смотрите в файле [`LICENSE`](./LICENSE).

---

## 📬 Контакты

**Авторы:**
- С.Ю. Добдин
- А.В. Скрипаль

**Издательство:** [Лань](https://lanbook.com/)

---

## ⭐ Поддержите проект

Если этот курс оказался полезным, поставьте **звезду** ⭐ репозиторию — это помогает другим найти его!

---

<p align="center">
  <i>«Наша задача — сделать алгоритмы помощниками, а не врагами»</i><br>
  — из введения книги
</p>
