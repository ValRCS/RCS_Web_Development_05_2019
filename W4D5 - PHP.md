# PHP
## Server Side Scripting Language
### PHP - general-purpose scripting language especially suited to web development.

* https://php.net/
![PHP](https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/1422px-PHP-logo.svg.png)


# Basic: How does a web server work? 
* https://computer.howstuffworks.com/web-server.htm
* https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server

## How do front-end,back-end.full-stack differ?
* https://blog.usejournal.com/front-end-back-end-full-stack-what-exactly-are-they-talking-about-fbd5d3fd4939


## How does a PHP web server work?
* https://guide.freecodecamp.org/php/
![PHP work](https://github.com/xeroxism/myImages/blob/master/FCC_guides/PHP-server-model.png?raw=true)


# Static vs dynamic web pages
* https://en.wikipedia.org/wiki/Static_web_page
![Static](https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Scheme_static_page_en.svg/750px-Scheme_static_page_en.svg.png)

* https://en.wikipedia.org/wiki/Dynamic_web_page
![Dynamic](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Scheme_dynamic_page_en.svg/750px-Scheme_dynamic_page_en.svg.png)

# Web Development Stacks

* [LAMP](https://en.wikipedia.org/wiki/LAMP_%28software_bundle%29)

![LAMP](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/LAMP_software_bundle.svg/600px-LAMP_software_bundle.svg.png)

* LAMP(Linux/Apache/MySQL/PHP)
* MEAN(Mongo/Express/AngularJS/Node)
* JAMstack
Many more

## Istalling xAMP type stacks (WAMP,LAMP,MAMP?)

Many different prebuild stacks
Cload installer Bitnami provides many convenient prebuilt stacks
* https://bitnami.com/stacks/infrastructure
Choose (WAMP/LAMP/MAMP)

## Hello world in PHP
* https://secure.php.net/manual/en/tutorial.firstpage.php

* https://secure.php.net/manual/en/tutorial.useful.php

# Tutorials

* https://www.php.net/manual/en/intro-whatis.php
* https://www.php.net/manual/en/
* https://www.guru99.com/what-is-php-first-php-program.html
* https://www.tutorialspoint.com/php7/
* https://www.w3schools.com/php7/default.asp
* https://www.tutorialrepublic.com/php-tutorial/
* https://developer.hyvor.com/tutorials/php/introduction

# Guides
# Books, resources

* https://phptherightway.com/

# Videos
* https://laracasts.com/series/php-for-beginners
FreeCodeCamp 4hour video
* https://www.youtube.com/watch?v=OK_JCtrrv-c

## Visual Studio Code plugins

* https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-pack

# PhpStorm manual
* https://www.jetbrains.com/help/phpstorm/quick-start-guide-phpstorm.html

## PHP Functions
* https://secure.php.net/manual/en/language.functions.php
* https://www.w3schools.com/php7/php7_functions.asp
* https://www.phpexercises.com/functions-php-exercises.html
* https://www.w3resource.com/php-exercises/php-function-exercises.php

### PHP Functions are NOT case-sensitive!
* https://stackoverflow.com/questions/33273941/php-case-sensitivity

## Variable scope in PHP
* https://secure.php.net/manual/en/language.variables.scope.php


## Include / require in PHP
* https://www.w3schools.com/PHP/php_includes.asp
* https://stackoverflow.com/questions/2418473/difference-between-require-include-require-once-and-include-once

## Object-Oriented PHP
* https://secure.php.net/manual/en/language.oop5.php
* https://secure.php.net/manual/en/language.types.object.php
* https://code.tutsplus.com/tutorials/object-oriented-php-for-beginners--net-12762
* https://stackoverflow.com/questions/1343619/php-real-world-oop-example
* https://www.killerphp.com/tutorials/php-objects-page-1/



## Creating a persistent hit counter

We need some way of storing data since PHP interpreter will "forget" each session once the page is served.

### Simplest(not necessarily the best) solution - store data in a text file
* http://php.net/manual/en/function.fopen.php

* http://justintadlock.com/web-design/counter
* https://stackoverflow.com/questions/18236599/visits-counter-without-database-with-php

### What happens when  many visitors access the page at the same time?

