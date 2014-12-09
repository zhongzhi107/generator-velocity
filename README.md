# Java Velocity Project generator

[Yeoman](http://yeoman.io) generator that scaffolds out a front-end web app with Jave Velocity template.

## Features

* CSS Autoprefixing
* Built-in preview server with LiveReload
* Automagically compile CoffeeScript & Sass
* Automagically lint your scripts
* Automagically inline image to css file use base64 encode.
* Awesome Image Optimization (via OptiPNG, pngquant, jpegtran and gifsicle)
* Mocha Unit Testing with PhantomJS
* Mave relative (Optional)

For more information on what `generator-velocity` can do for you, take a look at the [Grunt tasks](https://github.com/zhongzhi107/generator-velocity/blob/master/app/templates/_package.json) used in our `package.json`.


## Getting Started

- Install: `npm install -g generator-velocity`
- Run: `yo velocity`
- Run `grunt` for building and `grunt server` for preview[\*](#grunt-serve-note). 


## Docs

We have [recipes](docs/recipes) for integrating other popular technologies like LESS.


## Contribute

See the [contributing docs](https://github.com/yeoman/yeoman/blob/master/contributing.md).

Note: We are regularly asked whether we can add or take away features. If a change is good enough to have a positive impact on all users, we are happy to consider it.

If not, `generator-velocity` is fork-friendly and you can always maintain a custom version which you `npm install && npm link` to continue using via `yo velocity` or a name of your choosing.


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
