# tasks/config/coffee.js

Этот файл настраивает задачу Grunt под названием "coffee".

По умолчанию, этот файл компилирует файлы CoffeeScript, расположенные в [`assets/js/`](https://sailsjs.com/anatomy/assets/js/), в JavaScript, а затем генерирует новые файлы `.js` в `.tmp/public/JS/`.


### Но я не использую CoffeeScript...

Нет проблем!

Если вы не используете какую-либо предварительную обработку для клиентского JavaScript, просто проигнорируйте этот файл.

Если вы хотите использовать _другой_ препроцессор, например [TypeScript](https://www.typescriptlang.org/) или [Babel](https://babeljs.io/), и вы хотите, чтобы Sails обработал ваш клиентские JavaScript ресурсы автоматически во время работы, то вам повезло. В большинстве случаев это так же просто, как установить соответствующий плагин Grunt в зависимости от вашего приложения Sails, а затем настроить его для вывода скомпилированного JavaScript по тому же пути, что и в этой задаче по умолчанию.

Вот несколько популярных примеров:

+ [grunt-ts](https://www.npmjs.com/package/grunt-ts)
+ [grunt-babel](https://www.npmjs.com/package/grunt-babel)


### Использование

Дополнительная документация по использованию `grunt-contrib-coffee` смотрите [тут](https://npmjs.com/package/grunt-contrib-coffee).


<docmeta name="displayName" value="coffee.js">
