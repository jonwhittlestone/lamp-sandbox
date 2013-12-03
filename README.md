lamp-sandbox
============

A LAMP Virtual Machine for Virtualbox &amp; Cheatsheet

An appliance image for use with VirtualBox

[Download] ftp://whittlestone:Pa55word!@whittlestone.info/lampsandbox2.ova
## Features

* LAMP - 5.4.17
* [phpMyAdmin](http://lamp-sandbox.dev:8080/phpmyadmin/)
* Git
* MCrypt PHP Extension
* PHP5 curl extension
* Composer installed globally
* For SQL Server: [php5-sybase](http://blog.jamesrossiter.co.uk/2011/03/08/connecting-to-microsoft-sql-server-from-php-in-ubuntu-using-mssql_connect/)
* [Amend Freetds config](http://goo.gl/lQitH) to allow for UTF-8 communications
* [256 Colours](http://whiletruecode.tumblr.com/post/13358288098/enabling-256-color-mode-in-ubuntus-bash-terminal)
* Ruby 1.9.3 + Ruby Gems
* Rails 3.2.3
* node 0.6

For testing

* PHPUnit - 

---

## Instructions for use

1. Install VirtualBox and VirtualBox guest additions
2. Import the OVA file - File > Import Appliance
3. Edit the appliance's shared folder and the VM's lamp-sandbox vhost config if necessary 
4. Amend the host OS's hosts file  127.0.0.1 lamp-sandbox.dev
5. Visit http://lamp-sandbox.dev:8080/

## Cheatsheet

| Description        | Command          | Comments  |
| ------------- |:-------------:| -----:|
| URL     | `http://lamp-sandbox.dev:8080/` |  |
| SSH Connection      | `ssh -luser -p2222 lamp-sandbox.dev`      |   password: qwerty |
| zebra stripes | are neat      |    $1 |

