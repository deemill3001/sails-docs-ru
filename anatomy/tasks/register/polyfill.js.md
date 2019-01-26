# tasks/register/polyfill.js

Этот файл настраивает задачу Grunt под названием "polyfill".

Добавьте файл `polyfill.js` в общедоступные ресурсы (в режиме разработки) или минимизированный файл JavaScript (в продакшн), чтобы заполнить функции, отсутствующие в старых браузерах, таких как `Promise`. Эта задача предназначена для работы в сочетании с [задачей babel](https://sailsjs.com/documentation/anatomy/tasks/config/babel.js).

##### Разработка (`polyfill:dev`)

В режиме разрабаткт эта задача копирует файл polyfill в `.tmp/public/polyfill/polyfill.min.js` и гарантирует, что этот файл будет включен (через [задачу `linkAssets`](https://sailsjs.com/Documentation/anatomy/tasks/register/linkassets.js)) в виде тега `<script>` в любых файлах HTML с тегом шаблона `<!--SCRIPTS-->`.

> По умолчанию задачи `polyfill:dev` и `babel` закомментированы в задачах разработки Grunt, чтобы упростить отладку кода в браузере.

##### Продакшн (`polyfill:prod`)

В режиме продашкн (т.е. когда переменная окружения `NODE_ENV` установлена в `production`), эта задача добавляет содержимое файла polyfill в самый верх объединенного и уменьшенного файла `production.min.js`.

<docmeta name="displayName" value="polyfill.js">

