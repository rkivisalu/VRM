### Prerequisites

* php 7.0 or higher
```
sudo apt-get install php7.0-cli
sudo apt-get install php-xml
```

* [composer](https://getcomposer.org/download/)

* SQLite
```
sudo apt-get install php-sqlite3


### Setting up

Install the php 7.0 or higher package

\\ sudo apt-get install php7.0
\\ sudo apt-get install php7.0-xml

install SQlite
\\sudo apt-get install php7.0-sqlite3

download composer installer
\\ sudo curl -s https://getcomposer.org/installer | php

move the composer.phar file so it would be globally usable
\\ sudo mv composer.phar /usr/local/bin/composer

To install the software you have following options:

Cloning the project to your computer. If you have ssh access.

```
git glone git@gitlab.com:i-sepp/bcs-koolitus.git
```

Or download it manually from the gitlab [page](https://gitlab.com/i-sepp/bcs-koolitus).

Then you need to have composer installed in your computer.
And then you need to install composer packages in your project folder.
```
\\ composer install

make a folder for database

\\ mkdir database


Start the web server

\\ php -S localhost:8000 -t web


### Results

Go to localhost:8000 with your browser. 
You should see a form to add a new booking. If it's there, everything works well.
