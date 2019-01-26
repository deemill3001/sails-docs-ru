# tasks/config/concat.js

Этот файл настраивает задачу Grunt под названием "concat".

Он объединяет содержимое нескольких файлов JavaScript и/или CSS в два новых файла, каждый из которых находится в файлах `concat/production.js` и `concat/production.css` соответственно в `.tmp/public/concat`.

Это используется в качестве промежуточного шага для генерации монолитных файлов, которые затем могут быть переданы в `uglify` и/или `cssmin` для [минификации](https://ru.wikipedia.org/wiki/%D0%9C%D0%B8%D0%BD%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)).


### Использование

Дополнительная документация по использованию `grunt-contrib-concat` смотрите [тут](https://npmjs.com/package/grunt-contrib-concat).


<docmeta name="displayName" value="concat.js">
