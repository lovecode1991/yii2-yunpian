Yunpian-sdk for YII2
====================

云片还未出 PHP 的 SDK 支持，只提供了接口，现阶段正在使用 YII2 做开发，所以就把相应的组件共享出来，给需要的人用。

[![Build Status](https://travis-ci.org/dcb9/yii2-yunpian.svg?branch=master)](https://travis-ci.org/dcb9/yii2-yunpian)

## Install 

add `dcb9/yii2-yunpian` to composer.json

```
$ composer update 
```

OR

```
$ composer require dcb9/yii2-yunpian
```

## Usage

```php
# file app/config/main.php
<?php

return [
    'components' => [
	   'yunpian' => [
            'class' => 'dcb9\Yunpian\sdk\Yunpian',
            'apiKey' => 'your yunpian apiKey',
        ],
    ],
];
```
