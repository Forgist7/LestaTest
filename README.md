# Тестовое задание для Леста

### Задание 1:
1. Убедитесь что все файлы находятся в одной директории
2. Соберите контейнер командой: `docker build -t flask-ping-app .`
3. Запустите контейнер командой: `docker run -p 5000:5000 flask-ping-app`
4. Проверьте работоспособность командой: `curl http://localhost:5000/ping`

### Задание 2:
1. Убедитесь что все файлы находятся в одной директории
2. Запустите командой: `docker-compose up --build`
3. Проверьте работоспособность командами:  
   `curl http://localhost:5000/ping`  
   `curl http://localhost:5000/count`  
