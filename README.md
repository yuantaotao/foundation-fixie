foundation-fixie
================

Since IE6 is still the major in the [browser share in China](http://tongji.baidu.com/data/browser), it's NOT OK that [Foundation does not support IE6](http://foundation.zurb.com/docs/support.html).

This css hack will help.

Useage
=======
* use the css file

    `<!--[if lt IE 9]>`
    
    `<link href="/static/css/pc/fixie.css" rel="stylesheet" type="text/css">`
    
    `<![endif]-->`

* customize the sass file
You will need [Sass](http://sass-lang.com/) to build it.
