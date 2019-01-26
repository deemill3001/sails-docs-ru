# config/routes.js

Этот файл содержит пользовательские маршруты. Sails использует эти маршруты, чтобы определить, что делать каждый раз, когда он получает запрос.

Если Sails получает URL-адрес, который не соответствует ни одному из [пользовательских маршрутов](https://sailsjs.com/documentation/concepts/routes/custom-routes) в этом файле, он проверит соответствие [assets](https://sailsjs.com/documentation/concepts/assets) (изображения, сценарии, таблицы стилей и т. д.). Наконец, если они не совпадают, срабатывает [обработчик 404 по умолчанию](https://sailsjs.com/documentation/reference/response-res/res-not-found).

При первом создании приложения Sails в этом файле есть только один маршрут. Его работа - показывать домашнюю страницу.

Возможно, вы захотите добавить еще.

> Sails также внедряют _shadow маршруты_ или неявные маршруты, которые обрабатывают определенные виды запросов за кулисами. Для получения дополнительной информации об этих видах маршрутов см. **[Концепции > Чертежи](https://sailsjs.com/documentation/concepts/blueprints)**.

### Использование

См. [`sails.config.routes`](https://sailsjs.com/documentation/reference/configuration/sails-config-routes) для просмотра всех доступных опций.

<docmeta name="displayName" value="routes.js">
