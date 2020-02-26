GDPR Extention
==============
it saves hashed email with timestamp into the database

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist intermundia/yii2-gdpr "*"
```

or add

```
"intermundia/yii2-gdpr": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \intermundia\gdpr\AutoloadExample::widget(); ?>```