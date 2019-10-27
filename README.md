# HSDA Demo App

## Environment

**LAMP stack**
*	php >=7.1
*	Apache >=2.2
*	mod_rewrite


## Installation

Arrange Apache virtual host

`cd /target/folder`

`git clone https://github.com/sarapis/orapi-interface .`



Leave test API entry point or set new one into env.php file located at _/target/folder/include/env.php_

ex: `define('APIENTRY', 'http://example.com');`