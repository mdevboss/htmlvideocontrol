# [htmlvideo](http://htmlvideo.org/) : HTML5 Audio & Video for [jQuery](http://jquery.com/)

[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/happyworm/htmlvideo?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Support for [Zepto](http://zeptojs.com/) 1.0+ compiled with the data module.

## What is htmlvideo?

### htmlvideo is a jQuery/Zepto plugin that allows you to:
* **play and control media** files in your webpage.
* create a **consistent interface** and experience across all browsers.
* create and style a media player using **just HTML and CSS**.
* add **audio** and **video** to your jQuery/Zepto projects.
* support more devices using **HTML5**.
* support older browsers using a Flash _fall-back/forward_.
* control media on your website using a [JavaScript API](http://www.htmlvideo.org/latest/developer-guide/).

### htmlvideo supports:
* HTML5: **mp3, m4a (AAC), m4v (H.264),** ogv*, oga*, wav*, webm*
* Flash: **mp3, m4a (AAC), m4v (H.264),** rtmp, flv.

_(*) Optional counterpart formats to increase HTML5 cross-browser support._

## Bower Install
* simple install using `bower install htmlvideo`
* see <http://bower.io/> for more information.

## Composer install

Install htmlvideo via composer by adding the following lines to your `composer.json` in your project:

    // ...
    "require": {
        // ...
        "happyworm/htmlvideo": "2.*"
        // ...
    }
    // ...
    "config": {
        "component-dir": "your/desired/asset/path"
    },
    // ...

Then execute the following:

    php composer.phar update

Composer will now download all components and install the needed files into `your/desired/asset/path`, ready to use.

## License
[htmlvideo](http://htmlvideo.org/) is licensed under the [MIT license](http://opensource.org/licenses/MIT).

## More information:
* [htmlvideo.org](http://htmlvideo.org/)
* [Quick Start Guide](http://www.htmlvideo.org/latest/quick-start-guide/)
* [Developer Guide and API Reference](http://www.htmlvideo.org/latest/developer-guide/)

## Author:
Mark J Panaghiston [@thepag](http://twitter.com/thepag)
[happyworm.com](http://happyworm.com/)
