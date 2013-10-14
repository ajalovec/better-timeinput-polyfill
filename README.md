# better-timeinput-polyfill [![Build Status](https://api.travis-ci.org/chemerisuk/better-timeinput-polyfill.png?branch=master)](http://travis-ci.org/chemerisuk/better-timeinput-polyfill)
> `input[type=time]` polyfill for [better-dom](https://github.com/chemerisuk/better-dom)

[LIVE DEMO](http://chemerisuk.github.io/better-timeinput-polyfill/)

## Installing
Use [bower](http://bower.io/) to download this extension with all required dependencies.

    bower install better-timeinput-polyfill --save

This will clone the latest version of the __better-timeinput-polyfill__ into the `bower_components` directory at the root of your project.

Then append the following html elements on your page:

```html
<html>
<head>
    ...
    <!--[if IE]>
        <link href="bower_components/better-dom/dist/better-dom.htc" rel="better-dom-htc" />
        <script src="bower_components/html5shiv/dist/html5shiv.js"></script>
    <![endif]-->
</head>
<body>
    ...
    <script src="bower_components/better-dom/dist/better-dom.js"></script>
    <script src="bower_components/better-timeinput-polyfill/dist/better-timeinput-polyfill.js"></script>
</body>
</html>
```

## Browser support
* Chrome
* Safari 4+
* Firefox 16+
* Opera 12.10+
* IE8+