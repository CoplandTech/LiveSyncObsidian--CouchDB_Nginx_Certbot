# LiveSync Obsidian: CouchDB, Nginx, Certbot
Автоматическая сборка сервера CouchDB с доменном и SSL-сертификацией

Сделать файл исполняющим: chmod +x setup.sh

После получения SSL сертификата требуется перезагрузить NGINX - docker restart nginx

На текущий момент есть проблема с получением SSL :#

# Задачи:
1. Выбор директории
2. Запуск с HHTPS или без
3. Тестовая генерация или конечная
4. Раз в сколько часов\дней проверять SSL
5. Проверить перезапуск nginx после обновления конфигурации
