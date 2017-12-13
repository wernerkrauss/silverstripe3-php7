# silverstripe3-php7
Composer installable patch to get SilverStripe 3 running on PHP7

Installs a patch (basically https://github.com/lekoala/silverstripe-327 and some minor changes by Mark Guinn, see https://github.com/markguinn/silverstripe-framework/tree/patch-3-327) via composer, so you can run SilverStripe 3.2+ on PHP7.

Uses composer plugin https://github.com/netresearch/composer-patches-plugin to install the patch after a `composer install`

##Installation

Simply run

`composer require wernerkrauss/silverstripe-3-php7:^0.1.0`,

then change your server to run PHP7 and enjoy the speed it provides.

## Note for upgrading to SilverStripe 3.6+

As SilverStripe 3.6 runs on PHP7 out of the box, this patch isn't needed any more. You can safely uninstall it and enjoy the speed of PHP7.0
