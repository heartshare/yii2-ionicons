Yii 2 Ionicons Asset Bundle
===============================

Installation
------------
Add in `composer.json`:
```
{
    "require": {
        "gietos/yii2-ionicons": "2.0.*"
    }
}
```

Usage
-----
In view
```php
<?
// ...

gietos\yii\ionicons\AssetBundle::register($this);

```

or as dependency in your asset bundle
```php
<?
// ...

class AppAsset extends AssetBundle
{
	// ...

	public $depends = [
		// ...
		'\gietos\yii\ionicons\AssetBundle'
	];
}

```

Helper
------
```php

use gietos\yii\ionicons\Ion;

echo FA::icon('heart');
// <i class="ion ion-heart"></i>
```
