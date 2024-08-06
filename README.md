# LiveSync Obsidian: CouchDB, Nginx, Certbot
Автоматическая сборка сервера CouchDB с доменном и SSL-сертификацией

После загрузки файла на сервер, требуется сделать его исполняющим: ```chmod +x setup.sh```

Скрипт автоматически проверит установку ```Docker``` & ```Docker Compose```. В случае отсутстивия установок - автоматически установит их.

### Диалоговые окна

- [x] Запрос логина и пароля CouchDB. (Шифрование пароля не настроено, пароль хранится в открытом виде)
- [x] Запрос директории установки файлов решения. (Требуется указывать ```слеш``` только в начале: ```/DIR```)
- [x] Запрос доменного имени. (Реализация через ```localhost``` пока не настроена, да и не вижу в этом смысла, т.к. для синхронизации на смартфонах требуется SSL)
- [x] Запрос выбора ```HTTP``` или ```HTTPS```.
- [x] Запрос интервала проверки SSL сертификата. (Интервал указывается в часах - к сожалению пока не тестировалось обновление) 
