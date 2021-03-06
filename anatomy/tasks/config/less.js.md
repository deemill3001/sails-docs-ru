# tasks/config/less.js


Этот файл настраивает задачу Grunt под названием "less".

Его работа состоит в том, чтобы скомпилировать ваши файлы LESS в CSS.

По умолчанию компилируется только файл `assets/styles/importer.less`. Это позволяет вам самим управлять порядком, то есть импортировать ваши зависимости, миксины(mixins), переменные, перезагрузки и т.д., прежде чем использовать другие стили, более специфичные для приложения. Это зависит только от вас, и в зависимости от порядка, в котором вы пишете `@import`-ы в вашем файле LESS.

### Но я не использую LESS...

Нет проблем!

Если вы не используете _какой-либо_ препроцессор для своих таблиц стилей, просто проигнорируйте этот файл.

Если вы хотите использовать другой препроцессор, например [SASS](http://sass-lang.com/) или [Stylus](http://stylus-lang.com/), и вы хотите, чтобы Sails обработала ваш таблицы стилей автоматически, то вам повезло. В большинстве случаев это так же просто, как установить соответствующий плагин Grunt в зависимости от вашего приложения Sails, а затем настроить его для вывода скомпилированного CSS по тому же пути, что и в этой задаче по умолчанию.

Вот несколько популярных примеров:

+ [grunt-sass](http://npmjs.com/package/grunt-sass)
+ [grunt-contrib-stylus](https://npmjs.com/package/grunt-contrib-stylus)

### Использование

Дополнительная документация по использованию `grunt-contrib-less` смотрите [тут](https://npmjs.com/package/grunt-contrib-less).


<docmeta name="displayName" value="less.js">
