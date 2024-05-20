# DOCKER
# 1. Установка DOCKER
- Вводим команду: **apt-get update**
- После нее: **apt-get install -y docker-engine**
- Включаем DOCKER: **systemctl start docker** | **systemctl enable --now docker**
# 2. Установка контейнера hello-world
- Вводим: **docker pull hello-world**
- Смотрим список работающих контейнеров: **docker ps -a**
- Смотрим список скачанных контейнеров: **docker images**
# 3. Запуск контейнера
- Вводим: **docker run hello-world**
- Смотрим список работающих контейнеров: **docker ps -a**
- Смотрим список скачанных контейнеров: **docker images**
# 4. Остановка контейнера
- Вводим: **docker ps -a**
- Смотрим **CONTAINER ID**
- Вводим команду: **docker rm -v [CONTAINER]**
# 5. Удаление контейнера
- Вводим: **docker images** и смотрим *IMAGE ID*
- Вводим docker rmi [IMAGE ID]
