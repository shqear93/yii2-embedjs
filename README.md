this is a fork package from [mitrii/yii2-embedjs](https://github.com/mitrii/yii2-embedjs.git)

Yii2 embed JS
=============
Embed JS with IDE checking or intellisense

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist shqear/yii2-embedjs "*"
```

or add

```
"shqear/yii2-embedjs": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php \shqear\widgets\Embedjs::begin(); ?>
<script type="text/javascript">
    console.log('Hello, world!');
</script>
<?php \shqear\widgets\Embedjs::end(); ?>
```
