# Docker_Django_Nginx_PostgreSQL_Ubuntu
Собран на docker образ Django (Linux, nginx, Django, Postgres, Gunicorn) сервера. 
Задача решена с использованием Compose. В данном репозитории находится файл docker-compose.yml. 
Запуск проекта: 
  - Убедитесь, что порты 8000 и 5432 не заняты на хостовой машина
  - Склонируйте этот репозиторий на свою машину или просто скачайте файл docker-compose.yml.
  - В директории с файлом docker-compose.yml пропишите команду: docker-compose up(ждем 40 секунд после скачивания всех образов, чтобы все службы запустились). Данная команда создаёт контейнеры на основании compose-файла в текущей директории.
  - По адресу http://localhost:8000/admin/ доступна административная панель Django-проекта. Логин и пароль административной панели прописаны заранее.
  - Логин: admin, пароль: 123.
  - Ссылка на образ graceozavr/django_view в Docker Hub: [graceozavr/django_view](https://hub.docker.com/r/graceozavr/django_view). 
