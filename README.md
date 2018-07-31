# PHP on Docker

Rather than installing PHP on your machine, this provides a `php` scripts which
executes PHP inside a docker image. You should be able to use it as you are used
to.

## Installation

This is a [homesick castle][1], if you are familiar with it you just need to
clone and ensure `$HOME/bin` is in your `$PATH`.

If you have no clue what a [castle][1] is, it is also easy:

    $ curl -sL https://raw.githubusercontent.com/augustohp/carcassonne-docker-php/master/home/bin/php -o /usr/local/bin/php
    $ chmod a+x /usr/local/bin/php

You can change `/usr/local/bin/php` to anything you want, the `/usr/local/bin`
should be in you `$PATH` and `php` is how you are going to call the command.

[1]: https://github.com/technicalpickles/homesick
