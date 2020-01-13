Example how to install in composer 
==================
{
    "repositories": [
        {
            "type": "git",
            "url": "https://github.com/vencendor/var-dumper.git",
            "reference": "ven-master"
        }
    ],

    "require": {
        "symfony/var-dumper": "dev-vencendor",
        "digitickets/lalit": "^3.1"
    }

}




VarDumper Component
===================

The VarDumper component provides mechanisms for walking through any arbitrary
PHP variable. It provides a better `dump()` function that you can use instead
of `var_dump`.

Resources
---------

  * [Documentation](https://symfony.com/doc/current/components/var_dumper/introduction.html)
  * [Contributing](https://symfony.com/doc/current/contributing/index.html)
  * [Report issues](https://github.com/symfony/symfony/issues) and
    [send Pull Requests](https://github.com/symfony/symfony/pulls)
    in the [main Symfony repository](https://github.com/symfony/symfony)
