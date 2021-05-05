# PHP Docker Images

Images are built and tagged using both stable and version specific tags.

* `7.0`, `7.0-fpm`
* `7.1`, `7.1-fpm`
* `7.2`, `7.2-fpm`
* `7.3`, `7.3-fpm`
* `7.4`, `7.4-fpm`
* `8.0`, `8.0-fpm`

## Additional Extensions

These images are based on the `amazonlinux:2` image using the Remi's RPMs Repository to install PHP including the following extensions:

* bcmath
* gd
* gmp
* intl
* mbstring
* sodium | mcrypt
* mysqlnd
* opcache
* pdo
* process
* soap
* xml
* xmlrpc
* zip
* ldap

## Other Inclusions

* [composer](https://hub.docker.com/_/composer) - dependency manager for PHP packages
* git - version control system (used by composer)
* npm - package manager for the Node JavaScript platform
* patch - apply a diff file to an original (used by composer)
* unzip - list, test and extract compressed files in a ZIP archive (used by composer)
* pwgen - password generator used in scripting creation of passwords meeting specific criteria
* ncat - networking utility which reads and writes data across networks from the command line
* jq - commandline JSON processor for use in scripts and pipelines