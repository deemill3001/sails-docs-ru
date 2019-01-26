# tasks/register/

Эта папка содержит задачи Grunt, которые Sails запускает по умолчанию.

Дополнительную информацию см. в разделе [Ресурсы > Автоматизация задач > Триггеры задач](https://sailsjs.com/documentation/concepts/assets/task-automation#?task-triggers).

> Чтобы запустить пользовательский список задач, создайте файл в этом каталоге и установите[`sails.config.environment`](https://sailsjs.com/documentation/reference/configuration/sails-config#?sailsconfigenvironment) на название этого файла. Например, если конфигурация Sails `environment` установлена на "qa", то при запуске вместо `tasks/register/default.js` или `tasks/register/prod.js`, Sails будет запускать `tasks/register/qa.js`. (Если он не существует, вместо него будет запущен `default.js`.)

<docmeta name="displayName" value="register">

