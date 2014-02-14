Sasstarter
==========

A quick-start responsive framework for frontend development with Sass.

![Sasstarter](http://file.setetres.st/img/starter-header.gif?v=1.2&raw=true)

Version
-------

1.3.0 (#e32e21)

Plugins
-------

Starter use this:

* [Normalize.css] - A modern, HTML5-ready alternative to CSS resets.
* [jQuery] - A fast, small, and feature-rich JavaScript library.
* [jQuery Easing] - A jQuery plugin to give advanced easing options.
* [FitVids] - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
* [FullScreenBg] - A small jQuery plugin that allows you to create fullscreen background.
* [Modernizr] - JavaScript library that detects HTML5 and CSS3 features in the user’s browser.

Structure
---------

```
├── sassstarter/
│   ├── css/
│   │   ├── main.css             (sass output)
│   │   ├── main-responsive.css  (sass output)
│   │   └── normalize.css        (aplha male of css resets)
│   ├── sass/
│   │   ├── main.sass            (basic css configuration)
│   │   ├── main-responsive.sass
│   │   │   ├── 4col             (mobile - portrait view)
│   │   │   ├── 6col             (mobile - landscape view)
│   │   │   ├── 9col             (for devices with 800 wide)
│   │   │   ├── 12col            (for devices with 1024 wide)
│   │   │   └── 15col            (for devices with 1280+ wide)
│   ├── img/
│   │   └── loading.gif          (fake 'loading' background)
│   └── js/
│       ├── functions.js         (for your functions and shit)
│       ├── grid.js              (the visual guide for your layout)
│       ├── jquery.js            (jquery library)
│       ├── modernizr.js         (html5 + css3 for the masses)
│       └── plugins.js           (you can add more plugins here)
├── .gitignore
├── README.md                    (you're reading it right now)
├── bower.json                   (for installation via bower)
├── favicon.ico                  (16x16 of pure art)
└── index.html                   (duh!)
```

Installation via [Bower]
------------------------

```
bower install sasstarter
```

Using Sass
----------

To install Sass, start Command Prompt with Ruby and type

```
gem install sass
```

Running Sass:

```
sass sass/main.sass css/main.css
```

Compile with:

```
sass --watch sass/main.sass:css/main.css
```

Compile with (compressed):

```
sass --watch sass/main.sass:css/main.css --style compressed
```

License
-------

Sasstarter is under a [Creative Commons Attribution License].


[Bower]: http://github.com/bower/bower
[Normalize.css]: http://github.com/necolas/normalize.css
[jQuery]: http://github.com/jquery/jquery
[jQuery Easing]: http://github.com/gdsmith/jquery.easing
[FitVids]: http://github.com/davatron5000/FitVids.js
[FullScreenBg]: http://github.com/Gaya/Fullscreen-Background-jQuery-plugin
[Modernizr]: http://github.com/Modernizr/Modernizr
[Creative Commons Attribution License]: http://creativecommons.org/licenses/by/4.0
