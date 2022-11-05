### CarGuru test project with Sonata Admin Bundle and custom User Bundle

#### Prerequisites
- you should have installed php 7.4+ on your local machine configured with pdo_sqlite
- you should have installed [SYMFONY CLI](https://symfony.com/download) on your local machine 
- you should have installed [COMPOSER](https://getcomposer.org) on your local machine

#### Installation
- Clone this repository to local machine
- Go to the root folder
- Run command 
``` bash
$ composer install
```
- create new project user
``` bash
$ symfony console carguru:member:create <username> <password>
```
with this created user, you will login to admin area later
- Start local server with
``` bash
$ symfony serve
```
- navigate in your browser to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- enjoy

#### P.S.: Custom user bundle repository aka "carguru member bundle" &rarr; [here](https://github.com/janwebdev/carguru-member-bundle)