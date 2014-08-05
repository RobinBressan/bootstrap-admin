Bootstrap Admin
===============

Bootstrap Admin aims to provide an open source admin dashboard template based on [Bootstrap](http://getbootstrap.com).

It is built with [Compass](http://compass-style.org/) using [Sass](http://sass-lang.com/). The project try to respect Bootstrap standards to keep flexible and configurable.

Installation
============

To install the project you first need to install `bootstrap-sass` and `font-awesome-sass`:

```
sudo gem install bootstrap-sass
sudo gem install font-awesome-sass
```

Then you need - as mention above - Compass:

```
sudo gem install compass
```

Finally clone the project:

```
git clone git@github.com:RobinBressan/bootstrap-admin.git
```

Configuration
=============

See `config.rb` to config the css build dir

The default configuration build all into `example/css` folder.

Build
=====

During development run `make compass-watch` to rebuild on each change the css.

To compile the css for production run `make compass-compile`

Example
=======

An example template can be found into the `example` folder. Run `bower install` before to install dependecies.
