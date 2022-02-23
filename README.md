# Elevent's PHP Coding Standards

A custom PHP CodeSniffer ruleset

## Install

1. Add the repository to your composer.json:
    ```json
    "repositories": [
        {
            "type": "github",
            "url": "git@github.com:reelivate/php-coding-standards.git"
        }
    ]
    ```
1. Require with composer:
    ```shell
    composer require --dev reelivate/php-coding-standards
    ```

## Usage

1. Reference the ruleset in your `phpcs.xml` or `.phpcs.xml` configuration file:
    ```xml
    <?xml version="1.0"?>
    <ruleset>
        <file>./src</file>
        <file>./tests</file>

        <rule ref="./vendor/reelivate/php-coding-standards/ruleset.xml"/>
    </ruleset>
    ```
1. Run `phpcs`
