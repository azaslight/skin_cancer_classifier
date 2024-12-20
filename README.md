# skin_cancer_classifier
Классификация кожных образований с помощью нейронной сети для MODELATHON

# Классификатор рака кожи

Этот проект представляет собой модель глубокого обучения для классификации рака кожи на основе изображений кожных образований. Цель проекта — создать классификатор, который может определить, является ли данное кожное образование злокачественным или доброкачественным.

## Датасет
Проект использует **Skin Cancer MNIST (HAM10000)** датасет, который содержит более 10 000 аннотированных изображений кожных образований. Датасет включает различные типы кожных образований, и используется для обучения модели на основе сверточной нейронной сети (CNN) для точной классификации.

Датасет доступен на Kaggle [здесь](https://www.kaggle.com/datasets/ryanholbrook/skin-cancer-mnist-ham10000).

## Используемые технологии
- **Python**
- **TensorFlow** и **Keras** (для построения и обучения модели CNN)
- **Pandas** (для работы с данными)
- **Matplotlib** (для визуализации данных)
- **Scikit-learn** (для оценки модели)

## Особенности
- **Классификация изображений**: Классификация кожных образований как доброкачественных или злокачественных.
- **Модель CNN**: Используется сверточная нейронная сеть для высокой точности распознавания изображений.
- **Предобработка данных**: Включает этапы загрузки, изменения размера и нормализации изображений перед подачей их в модель.

## Требования
Для установки зависимостей выполните команду:

```bash
pip install -r requirements.txt
```


# Классификатор рака кожи

Этот проект представляет собой модель глубокого обучения для классификации рака кожи на основе изображений кожных образований. Цель проекта — создать классификатор, который может определить, является ли данное кожное образование злокачественным или доброкачественным.

## Датасет
Проект использует **Skin Cancer MNIST (HAM10000)** датасет, который содержит более 10 000 аннотированных изображений кожных образований. Датасет включает различные типы кожных образований, и используется для обучения модели на основе сверточной нейронной сети (CNN) для точной классификации.

Датасет доступен на Kaggle [здесь](https://www.kaggle.com/datasets/ryanholbrook/skin-cancer-mnist-ham10000).

## Используемые технологии
- **Python**
- **TensorFlow** и **Keras** (для построения и обучения модели CNN)
- **Pandas** (для работы с данными)
- **Matplotlib** (для визуализации данных)
- **Scikit-learn** (для оценки модели)

## Особенности
- **Классификация изображений**: Классификация кожных образований как доброкачественных или злокачественных.
- **Модель CNN**: Используется сверточная нейронная сеть для высокой точности распознавания изображений.
- **Предобработка данных**: Включает этапы загрузки, изменения размера и нормализации изображений перед подачей их в модель.

## Требования
Для установки зависимостей выполните команду:

```bash
pip install -r requirements.txt
```
Разворачивание Telegram-бота
Этот проект включает в себя Telegram-бота, который использует модель классификации рака кожи для обработки изображений, присылаемых пользователями. Бот предсказывает, является ли изображение кожного образования злокачественным или доброкачественным.

Шаги для запуска бота:
Создайте нового бота через BotFather в Telegram и получите API Token.

Вставьте полученный API Token в переменную API_TOKEN в коде.

Убедитесь, что у вас установлены все зависимости:

bash
Копировать код
pip install -r requirements.txt
Запустите бота:

bash
Копировать код
python telegram_bot.py
Отправьте изображение через Telegram-бота. Бот ответит, указав, является ли изображение кожного образования опасным.

Используемые технологии:
Python
TensorFlow и Keras (для классификации изображений)
Python-telegram-bot (для интеграции с Telegram API)
PIL (Pillow) (для работы с изображениями)
Функционал:
Команда /start: Приветствие от бота и информация о его функционале.
Отправка изображения: Бот обрабатывает изображение кожного образования и дает предсказание (доброкачественное или злокачественное).
