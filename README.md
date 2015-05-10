HenterGEO
=========
基于Symfony2和MongoDB的地理位置查询演示

Install
-------
```
$ git clone https://github.com/lamjack/HenterGEO
$ cd HenterGEO/
$ composer update
$ cp app/config/parameters.yml.dist app/config/parameters.yml
$ php app/console doctrine:mongodb:schema:update
$ php app/console geo:data:import
```
