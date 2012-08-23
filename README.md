* Install composer (if not)

```
curl -s https://getcomposer.org/installer | php
```

* create a new project (use your kata name instead 'kataName')

```
php composer.phar create-project gonzalo123/phpkata kataName
```

* change directory to the new kata directory:

```
cd phpkata
```

* Run unit tests:

```
bin/phpunit
```

It creates one dummy class named Kata\DeleteMe (lib/Kata/DeleteMe.php)
and one test file (tests/DeleteMeTest.php)

Remove them and start coding.

Autoloader is set up according to psr-0 in lib folder

