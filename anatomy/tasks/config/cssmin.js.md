# tasks/config/cssmin.js

Этот файл настраивает задачу Grunt под названием "cssmin".

Оно минимизирует промежуточную объединенную таблицу стилей CSS, которая была подготовлена задачей `concat` в `.tmp/public/concat/production.css`. Вместе с задачей `concat`, это последний шаг, который минимизирует все CSS-файлы из `assets/styles/` (и, возможно, ваш файл импорта LESS из `assets/styles/importer.less`).

### Использование

Дополнительная документация по использованию `grunt-contrib-cssmin` смотрите [тут](https://npmjs.com/package/grunt-contrib-cssmin).


<docmeta name="displayName" value="cssmin.js">
