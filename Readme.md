Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

Нам предоставили данные с комментариями пользователей интернет-магазина. В них присутствует разметка о токсичности комментария. Используя эти данные нам необходимо создать модель которая сможет классифицировать комментария на позитивные и негативные. Модель будет считаться успешной если мы получим метрику качества F1 больше 0.75 на тестовых данных.

Прочитаем данные, изучим их и подготовим для использования с моделями машинного обучения. Так как предоставлен только один файл, нам нужно будет разбить данные на выборки для обучения и тестирования. Обучим несколько моделей, сравним их на тренировочных данных, выберем лучшую и посмотрим как она справится с тестовой выборкой.