# tasks/config/copy.js

Этот файл настраивает задачу Grunt под названием "copy".

Эта задача копирует файлы и/или папки из вашего каталога `assets/` в корневой веб-каталог (`.tmp/public`), чтобы они могли обслуживаться через HTTP, а также для дальнейшей предварительной обработки другими задачами Grunt.

##### Обычное использование (`sails lift`)
Копирует все каталоги и файлы (кроме CoffeeScript и LESS) из папки `assets/` в корневой веб-каталог - обычно это скрытый каталог, расположенный в `.tmp/public`.

##### Использование через список задач `build` (`sails www`)
Копирует все каталоги и файлы из каталога `.tmp/public` в каталог www.

### Использование

Дополнительная документация по использованию `grunt-contrib-copy` смотрите [тут](https://npmjs.com/package/grunt-contrib-copy).


<docmeta name="displayName" value="copy.js">
