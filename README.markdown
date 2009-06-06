# Doctrine ORM with Zend Framedwork and ZFDebug

This is a proof of concept to have Doctrine data in a ZFDebug panel.

To try this demo project, you need to put these libs in the `library` folder

- [Zend Framework](http://framework.zend.com/) 1.8.x
- [ZFDebug](http://code.google.com/p/zfdebug/) 1.5.x
- [Doctrine](http://www.doctrine-project.org/) 1.1.x

It should look like:

    library/
      Zend/
      Doctrine/
      Doctrine.php
      ZFDebug/

If you use the sqlite database, make sure that it is readable/writable by the web server

## More about ZF and Doctrine

For more information, visit

- [Doctrine ORM and Zend Framework](http://www.danceric.net/2009/06/06/doctrine-orm-and-zend-framework/)
- [ZFDebug and Doctrine ORM](http://www.danceric.net/2009/06/06/zfdebug-and-doctrine-orm)