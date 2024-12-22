# Анализатор здоровья зубов

## Для запуска

- Запускаем полностью `Airflow.ipynb`
- Открываем url и переходим в UI Airflow, проверяем корректность запуска(нет уведомлений о ошибках + даги запущены)
- отключаем ngrok: `ngrok.kill()`
- Переходим в другой ноутбук `Teeth.ipynb`
- Запускае его полностью
- Подставляем ссылку в переменные Airflow `airflow variable set url <URL>`
- Отправляем фото зубов в канал бота и ждем результата

## Ссылки

- tg: @BigEduBot
- [Airflow.ipynb](https://colab.research.google.com/drive/1mknTuB0zIrAPibQ5G4NgGzikVOs4IH6T?usp=sharing)
- [Teeth.ipynb](https://colab.research.google.com/drive/1TCGdm0T6-EhYhwuUvfyTUXf8qoCcDcgC?usp=sharing)
