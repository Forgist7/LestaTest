Тестовое задание для Леста

Задание 1:
Убедитесь что все файлы находятся в одной директории
Соберите контейнер командой: docker build -t flask-ping-app .
Запустите контейнер командой: docker run -p 5000:5000 flask-ping-app
Проверьте работоспособность командой: curl http://localhost:5000/ping

Задание 2:
Убедитесь что все файлы находятся в одной директории
Запустите командой: docker-compose up --build
Проверьте работоспособность командами: 
  curl http://localhost:5000/ping
  curl http://localhost:5000/count
