# Проект Kittygram

## Суть данного репозитория заключается в получении практических навыков(DevOps'а) в создании автоматизированного процесса деплоя на сервер(CI/CD) с использованием технологий Docker и GitHub Actions. В ходе работы были приобретены следующие навыки:

1. Написание конфигурационных файлов **Dockerfile** для *Django-приложения(backend)*, *React-приложения(frontend)* и *Nginx*. :heavy_check_mark:
2. Написание инструкции для системы сборки **Docker Compose**, в которую входят образы: *Django-приложения*, *React-приложения*, *PostgreSQL* и *Nginx*. :heavy_check_mark:
3. Подключения **Docker Volume** к приложениям для хранения в них статики, файлов БД и медиа файлов загружаемых пользователями. :heavy_check_mark:
4. Настройки *Django-приложения* для работы с *PostgreSQL*. :heavy_check_mark:
5. Написание инструкции для **GitHub Actions**(CI/CD) при помощи которой идет: проверка кода *Django-приложения* на соответствие **PEP8**, запуск тестов для *Django-приложения* и *React-приложения*, сборка и отправка образов на **DockerHub**, обновление образов и перезагрузка приложений на сервере при помощи **Docker Compose**, выполнение команд для запуска миграций БД, сборки и последующего перемещения статики в **volume**. :heavy_check_mark:


<br>**Это второй финальный спринт из курса "Управление проектом на удалённом сервере Ver.2.0" от Яндекс.Практикум*