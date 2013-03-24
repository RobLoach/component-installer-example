Component Installer Example
===========================

An example of using [Component Installer](http://robloach.github.com/component-installer)
with jQuery and Twitter Bootstrap. This makes use of the generated
[RequireJS](http://requirejs.org) configuration.

Usage
-----

1. Build with Composer:

    $ curl -s https://getcomposer.org/installer | php
    $ composer.phar install

2. Load `public/index.html` in your favourite web browser

3. If the text is green, then jQuery is loaded properly through RequireJS.

4. If clicking on "Launch demo modal" pops up a modal window, then Bootstrap is
   working correctly through RequireJS.
