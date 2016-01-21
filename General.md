### Installation ###

Download and extract the .zip in to your web directory.

Create a MySQL database called `ipam` and add a user/password.

Run the ipam`_`mysql`_`setup.sql against the database just created to import the tables and structure.

Edit the db.php file located in the `inc` folder. You need to enter your database user/password and also the location of the database server.

That's it. Enjoy!!

_This has only been tested with PHP5/MySQL/Apache2 on a linux server. I have a ping function that is used for generating an available IP address or searching for an IP that uses the php exec command to run a bash ping._

### Screenshots ###

_Your menus may look different. These screens are from a production system with specific customizations._

**Home Page**

![http://ip-address-management.googlecode.com/files/screen1.png](http://ip-address-management.googlecode.com/files/screen1.png)

**IP List**

![http://ip-address-management.googlecode.com/files/screen2.png](http://ip-address-management.googlecode.com/files/screen2.png)

**Greybox Edit Screen**

![http://ip-address-management.googlecode.com/files/screen3.png](http://ip-address-management.googlecode.com/files/screen3.png)