![Graph](https://github.com/phonetworks/commons-php/raw/master/.github/cover2.jpg "Phở Networks")

# commons-php
A repository of common files shared by Pho stack PHP projects.

## Coding Standards

* Use logging.
* info for debugging, warning for serious issues.


## Directory Structure

## Project Structure

## Pre-commit Procedures

* Make sure you have unit tests in regards to your contribution.
* Run ```vendor/bin/phpunit``` to make sure the code passes all tests. 
* Use ```vendor/bin/phpcs src``` to check for coding standards.
* Run ```vendor/bin/phpcs --report=diff src``` for a more detailed look.
* Use ```vendor/bin/phpcbf src``` to fix non-standard coding.
* Run ```vendor/bin/phpunit``` again to avoid any potential problems with php_codesniffer.
