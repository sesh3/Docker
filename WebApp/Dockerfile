#исходный образ
FROM python:3.8
#команда перед созданием образа
RUN mkdir -p /usr/src/app
#рабочая дериктрория
WORKDIR /usr/src/app
#копирования в дериктрорию внутри контейнера
COPY . /usr/src/app
#команда перед созданием образа
RUN pip install --no-cache-dir -r requirements.txt
#Декларирования проброски портов
EXPOSE 8080
#выполнить при запуске контейнера
CMD ["python", "app.py"]