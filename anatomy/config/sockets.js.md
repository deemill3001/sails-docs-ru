# config/sockets.js

Это файл конфигурации, который позволяет вам настраивать способ взаимодействия вашего приложения с клиентами через Socket.IO.

Он обеспечивает прозрачный доступ к инкапсулированному серверу Sails pubsub/socket для полной настройки. В нем вы можете делать вещи из списка ниже (и многое другое!).

- Переопределить функцию afterDisconnect (функция на стороне сервера)
- Определить пользовательскую логику авторизации для клиентских подключений
- Установить способ переноса
- Изменить интервал Heartbeat
- Изменить хранилище сокетов

### Больше информации
> Параметры конфигурации Socket.IO можно найти [здесь](https://github.com/LearnBoost/Socket.IO/wiki/Configuring-Socket.IO).

### Использование

См. [`sails.config.sockets`](https://sailsjs.com/documentation/reference/configuration/sails-config-sockets) для просмотра всех доступных параметров.


<docmeta name="displayName" value="sockets.js">
