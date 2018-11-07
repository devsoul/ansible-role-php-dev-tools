phpdevtools Ansible Role
----------------
    Codeception
    Composer
    Phan
    Phing
    PHP_CodeSniffer
    PHP Copy/Paste Detector
    PHP Coding Standards Fixer
    PHPLOC
    PHP Mess Detector
    PhpMetrics
    PHPStan
    PHPUnit
    Psalm
    Psysh

        
Requirements
------------
  - minimum `php 7.1`

Role Variables
--------------
None

Dependencies
------------
    - devsoul.codeception
    - devsoul.composer
    - devsoul.phan
    - devsoul.phing
    - devsoul.phpcodesniffer
    - devsoul.phpcpd
    - devsoul.phpcsfixer
    - devsoul.phploc
    - devsoul.phpmd
    - devsoul.phpmetrics
    - devsoul.phpstan
    - devsoul.phpunit
    - devsoul.psalm
    - devsoul.psysh

Example Playbook
----------------
    - hosts: php
      roles:
        - devsoul.phpdevtools

Check if it's installed:
------
    codecep --version
    composer --version
    phan --version
    phing --version
    php-cs-fixer --version
    phpcbf --version
    phpcpd --version
    phpcs --version
    phploc --version
    phpmd --version
    phpmetrics --version
    phpstan --version
    phpunit --version
    psalm --version
    psysh --version

License
-------
MIT

Author Information
------------------

:-)
