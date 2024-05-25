
Данный проект нацелен на разработку и усовершенствование чат-бота в Telegram с использованием нейронных сетей. Он предусматривает создание системы, способной предоставлять пользователю список фильмов по заданным параметрам.
Целью работы является снижение времени на поиск и подбор фильмов по определенным параметрам.
Задачи для достижения цели: 
1) Получить данные из API Кинопоиска
2) Обработать данные (токенизация, лемматизация, удаления стоп-слов, векторизация с помощью LSTM)
3) Обучения и тестирования модели CatBoostClassifier для получения жанров из запроса пользователя, а также модели LSTM для получения эмбеддингов
4) Реализация Телеграм-бота и интеграция в него моделей
5) Тестирование приложения и фикс ошибок

Архитектура LSTM:
![image](https://github.com/andromeda123248/Dip/assets/85245425/1d362f65-9034-4c29-99a3-3ef40613b7a2)

UML-диаграмма последовательности:
![image](https://github.com/andromeda123248/Dip/assets/85245425/33f26574-9061-4d9c-aa65-a20d1ed33a9f)
