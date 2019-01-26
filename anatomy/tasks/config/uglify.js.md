# tasks/config/uglify.js

Этот файл настраивает задачу Grunt под названием "uglify".

Его работа заключается в <a target="_blank" href="https://ru.wikipedia.org/wiki/%D0%9C%D0%B8%D0%BD%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)">минификации</a> клиентских JavaScript-файлов. Внутренне файл использует [UglifyES](https://www.npmjs.com/package/uglifyes).

### Использование

Дополнительная документация по использованию `grunt-contrib-uglify` смотрите [тут](https://github.com/gruntjs/grunt-contrib-uglify/tree/harmony).

### ES8 и выше

Пакет по умолчанию способен минимизировать JavaScript, написанный с использованием синтаксиса и функций ES6, ES7 и ES8, даже без [переноса](https://sailsjs.com/documentation/concepts/assets/default-tasks#?babel). Однако, если вы планируете поддерживать старые браузеры, которые не поддерживают ES6, рекомендуется по-прежнему переносить код (оставив значение по умолчанию [`babel`](https://sailsjs.com/documentation/anatomy/tasks/config/babel.js) и [`polyfill`](https://sailsjs.com/documentation/anatomy/tasks/register/polyfill.js) задачи на месте).

<docmeta name="displayName" value="uglify.js">
