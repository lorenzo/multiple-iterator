# MultipleIterator implementation for HHVM

This package offers a pure PHP-implementation of the MultipleIterator class
siince [HHVM does not implement MultipleIterator](https://github.com/facebook/hhvm/issues/5350).

It is safe to `composer require lorenzo/multiple-iterator` in any project even if not using HHVM, as the
class will only be included for HHVM.

# License

Unfortunately, unknown. The code was copied from
[The original author site](http://blog.somabo.de/2008/01/multipleiterator-for-php.html).
Since, the code made its way to the PHP source code, I'd assume this is under the
[PHP License](http://php.net/license/3_01.txt)
