# FancyIndex

Fancy and responsive theme for Apache directory & file listings, using a bit of [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate).

## Installation

- Customize `httpd-autoindex.conf`, copy and replace it with the one in Apache config folder (for example `/etc/apache2/extra/` in OS X, or `%ProgramFiles%\WAMP\bin\apache\apache2.4.9\conf\extra` in WAMP.
Don't worry about backup, you should already have it in `original/` folder.
- Make sure to point to the local `fancyindex` folder in the `httpd-autoindex.conf` directives.
- Make sure if mod_autoindex is on (in `httpd.conf` file)
- Restart server.

## Screenshot

![FancyIndex in action on a computer and smartphone.](https://raw.github.com/Tymek/fancyindex/master/screenshot.png)  

## TODO

- Move `style.css` into `main.css`

## Footnotes

Based on [apache-autoindex-theme](https://github.com/fuchcz/apache-autoindex-theme).

Screenshot thanks to [PlaceIt by Breezi](http://placeit.breezi.com/).

Icons by [Yusuke Kamiyamane](http://p.yusukekamiyamane.com/).  
All rights reserved. Licensed under a Creative Commons Attribution 3.0 License.

Feel free to modify.
