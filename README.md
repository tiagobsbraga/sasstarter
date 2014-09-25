Sasstarter
==========

A quick-start responsive framework for frontend development with Sass.

![Sasstarter](http://file.setetres.st/img/starter-header.gif?v=1.4&raw=true)

Version
-------

1.0.0 (#bef202)

Plugins
-------

Sasstarter use this:

* [Normalize.css] - A modern, HTML5-ready alternative to CSS resets.
* [jQuery] - A fast, small, and feature-rich JavaScript library.
* [jQuery Easing] - A jQuery plugin to give advanced easing options.
* [Modernizr] - JavaScript library that detects HTML5 and CSS3 features in the user’s browser.

Structure
---------

```
sasstarter/
├── bower_components/
│
├── css/
│   ├── main.css                (sass output)
│   └── normalize.css           (aplha male of css resets)
│
├── img/
│   └── loading.gif             (fake 'loading' background)
│
├── js/
│   ├── main.js                 (main js file application)
│   ├── grid.js                 (the visual guide for your layout)
│
├── psd/
│   └── grid.psd                (for designers)
│
│── sass/
│   ├── main.sass               (basic sass configuration)
│   └── main-responsive.sass
│       ├── 4col                (mobile - portrait view)
│       ├── 6col                (mobile - landscape view)
│       ├── 9col                (for devices with 800 wide)
│       ├── 12col               (for devices with 1024 wide)
│       └── 15col               (for devices with 1280+ wide)
│
├── .gitignore                  (ignore this. ignore that)
├── README.md                   (you're reading it right now)
├── bower.json                  (for installation via bower)
├── favicon.ico                 (16x16 of pure art)
└── index.html                  (duh!)
```

Installation dependencies with [Bower]
------------------------

```
bower install sasstarter
```

Using [Sass]
----------

Install Sass

```
gem install sass
```

Run Sass:

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

-------

Copy of [Seventy Three] Project.

[Seventy Three]: http://setetres.st
[Bower]: http://github.com/bower/bower
[Sass]: http://github.com/nex3/sass
[Normalize.css]: http://github.com/necolas/normalize.css
[jQuery]: http://github.com/jquery/jquery
[jQuery Easing]: http://github.com/gdsmith/jquery.easing
[Modernizr]: http://github.com/Modernizr/Modernizr
[Creative Commons Attribution License]: http://creativecommons.org/licenses/by/4.0
