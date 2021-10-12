# play-with-docker

Данный репозиторий предназначен для запуска различных сервисов на бесплатной основе на 4 часа

# Быстрый старт:

0.  Логинимся/Регестрируемся на сервисе:
    
    https://labs.play-with-docker.com

1.  Копируем репозиторий себе на ПК:

        git clone git@github.com:github-devops/play-with-docker.git

2.  Запускаем скрипт:

        ./deploy.sh <SERVICE> <URL_FOR_SSH>

    SERVICE - название сервиса, который хотим запустить, т.е. название директории соответсвует названию сервиса
    URL_FOR_SSH выглядит так: ip172-18-0-70-c4437qfnjsv0008hvac0@direct.labs.play-with-docker.com,
    его необходимо скопировать из веб-панели, после запуска инстанса
