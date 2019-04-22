![Graph](https://github.com/phonetworks/commons-php/raw/master/.github/cover-smaller.png "Phở Networks")

# commons-php
A repository of common files shared by Phở stack PHP projects.

## Coding Standards

* Use logging.
* info for debugging, warning for serious issues.
* PSR-1 and PSR-2
* \_ prefix for in-class helper methods
* \_\_ prefix for duplicate method names imported from traits.
* "hy" prefix for "hydrated" methods.


## Directory Structure

## Project Structure

## Pre-commit Procedures

* Make sure you have unit tests in regards to your contribution.
* Run ```vendor/bin/phpunit``` to make sure the code passes all tests. 
* Use ```vendor/bin/phpcs src``` to check for coding standards.
* Run ```vendor/bin/phpcs --report=diff src``` for a more detailed look.
* Use ```vendor/bin/phpcbf src``` to fix non-standard coding.
* Run ```vendor/bin/phpunit``` again to avoid any potential problems with php_codesniffer.

## Links

* https://github.com/thephpleague/skeleton
* http://www.php-fig.org/
