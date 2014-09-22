Yii2 embed JS
=============
Embed JS with IDE checking or intellisense

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist mitrii/yii2-embedjs "*"
```

or add

```
"mitrii/yii2-embedjs": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php \mitrii\widgets\Embedjs::begin(); ?>
<script type="text/javascript">
    console.log('Hello, world!');
</script>
<?php \mitrii\widgets\Embedjs::end(); ?>
```
