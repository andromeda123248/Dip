  Данный проект нацелен на разработку и усовершенствование чат-бота в Telegram с использованием нейронных сетей. Он предусматривает создание системы, способной предоставлять пользователю список фильмов по заданным параметрам.
Целью работы является снижение времени на поиск и подбор фильмов по определенным параметрам.

Аннотация:

1) [**Movie Recommendation Module.py**](https://github.com/andromeda123248/Dip/blob/main/Movie%20Recommendation%20Module.py) - Реализация проекта, состоящая из подготовки данных examples.json, реализация модели CatBoostClassifier для генерации жанра фильмов, реализация модели LSTM для получения эмбеддингов описаний фильмов, генерация наиболее подходящих фильмов к запросу пользователя;
2) [**Telebot Realisation.py**](https://github.com/andromeda123248/Dip/blob/main/Telebot%20Realisation.py) - Создания Telegram-бота с фреймворком telebot;
3) [**examples.json**](https://github.com/andromeda123248/Dip/blob/main/examples.json) - Датасет в формате JSON, полученный из API Кинопоиска, включающий в себя информацию о названиях фильмов, описаний и жанрах;
4) [**SentenceTransformer Method.ipynb**](https://github.com/andromeda123248/Dip/blob/main/SentenceTransformer%20Method.ipynb) - Метод решения задачи на основе модели Sentence Transformer;
5) **catboost_model** - Обученная модель CatBoostClassifier
6) **lstm_model.pth** - Обученная модель LSTM
