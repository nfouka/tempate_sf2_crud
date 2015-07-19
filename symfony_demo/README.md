Symfony CRUD Application
========================

The "Symfony crud Application" is a reference application created to show how
to develop Symfony applications following the recommended best practices.

Requirements
------------

  * PHP 5.3 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements](http://symfony.com/doc/current/reference/requirements.html).

Installation
------------

First, install the [Symfony Installer](https://github.com/symfony/symfony-installer)
if you haven't already. Then, install the Symfony Demo Application executing
this command anywhere in your system:



Usage
-----

If you have PHP 5.4 or higher, there is no need to configure a virtual host
in your web server to access the application. Just use the built-in web server:

```bash
$ cd tempate_sf2_crud
$ php app/console server:run 127.0.0.1:4500
```

This command will start a web server for the Symfony application. Now you can
access the application in your browser at <http://127.0.0.1:4500>. You can
stop the built-in web server by pressing `Ctrl + C` while you're in the
terminal.

