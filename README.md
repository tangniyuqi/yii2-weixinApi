## Install

add `tangniyuqi/yii2-weixinapi` to composer.json

```sh
$ composer install
```

```
$ php composer.phar require tangniyuqi/yii2-weixinapi "*"
```

or add

```
"tangniyuqi/yii2-weixinapi": "*"
```

to the ```require``` section of your `composer.json` file.

## Usage

in action:

```
use tangniyuqi\weixinapi\base\Weixin;

new Weixin($config);

```