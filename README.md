## Sylius demo with ElasticSearch plugin ##

This is a Sylius demo with integrated [ElasticSearch plugin](https://github.com/Lakion/SyliusElasticSearchBundle).
Demonstrates how to add a product search box into the shop.
You can clone this repository and play with it or check this [commit](https://github.com/mheki/sylius-search-demo/commit/3d92f7) 
which contains all the code needed to add this feature to Sylius.

Installation
------------
Make sure ElasticSearch is running.

```bash
$ composer install
$ yarn install
$ yarn run gulp
$ php bin/console sylius:install
$ php bin/console fos:elastica:populate
$ php bin/console server:start
$ open http://localhost:8000/
```

![Search Box](https://i.stack.imgur.com/1uNde.jpg)