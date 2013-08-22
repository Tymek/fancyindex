# FancyIndex

Fancy and responsive theme for Apache directory & file listings, using a bit of [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate).

## Installation

- Customize `httpd-autoindex.conf` and replace the one in `/etc/apache2/extra/` (on OS X) with it.  
Don't worry about backup, you should already have `/etc/apache2/original/`.
- Make sure to point to the local `fancyindex` folder in the `httpd-autoindex.conf` directives.
- Make sure if mod_autoindex is on (in `httpd.conf` file)
- Restart server.

## Screenshot

![Picture of FancyIndex in action on a computer.](https://raw.github.com/mcdado/fancyindex/master/screenshot.jpg)  
Thanks to [PlaceIt by breezi](http://placeit.breezi.com/) for the screenshot.

![An iPhone screenshot of FancyIndex.](https://raw.github.com/mcdado/fancyindex/master/screenshot_iphone.jpg)  


## TODO

- Move `style.css` into `main.css`
- Move to [FontAwesome](http://fortawesome.github.io/Font-Awesome/) for Retina-ready icons

## Footnotes

Strongly based on [apache-autoindex-theme](https://github.com/fuchcz/apache-autoindex-theme).

Fork of [Tymek/fancyindex](https://github.com/Tymek/fancyindex).

Icons by [Yusuke Kamiyamane](http://p.yusukekamiyamane.com/).  
All rights reserved. Licensed under a Creative Commons Attribution 3.0 License.

Feel free to modify.
