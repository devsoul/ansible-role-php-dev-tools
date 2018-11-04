phpdevtools Ansible Role
----------------
    Codeception
    Composer
    PHPUnit
    PHP Coding Standards Fixer
    PHP_CodeSniffer
    PHP Mess Detector
    PHP Copy/Paste Detector
    PHPLOC
    PHPStan
    PhpMetrics

        
Requirements
------------
  - minimum `php 7.1`

Role Variables
--------------
None

Dependencies
------------
None

Example Playbook
----------------
    - hosts: php
      roles:
        - devsoul.phpdevtools

Check if it's installed:
------
    codecep --version
    composer --version
    phpunit --version
    php-cs-fixer --version
    phpcs --version
    phpcbf --version
    phpmd --version
    phpcpd --version
    phploc --version
    phpstan --version
    phpmetrics --version

License
-------
MIT

Author Information
------------------

:-)
