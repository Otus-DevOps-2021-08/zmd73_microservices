# zmd73_microservices
zmd73 microservices repository

Установлены docker docker-compose docker-machine
Выполнена сборка образа и отправка его в удалённый репозиторий
Выполнено подключение к удалённому инстансу при помощи docker-machine и запуск образа там образа
Добавил terraform манифесты, ansible плейбуки, шаблоны пакера для запуска и конфигурирования приложения в докере


Docker: сети,docker-compose
Добавил docker-compose файл с описанием микросервисов и сетей
Параметризовал некоторыые переменные для docker-compose файла
Добавил переменную COMPOSE_PROJECT_NAME, с помощью которой можно изменять префиксы контенеров
Добавил docker-compose.override файл с монтированием директорий (чтобы код был доступен приложению) и запуском puma в дебаг режиме с двумя воркерами
