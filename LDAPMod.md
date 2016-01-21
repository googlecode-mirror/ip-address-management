# To Add Threaded LDAP Auth #

  * Extract the ipam\_auth.zip to the root of IPAM.

  * Update the `inc/ldap.php` file to reflect your domain settings.

  * Update the `*authfrm*` function in `inc/functions.inc.php` by changing "MYGORUP" to the name of the group you wish to allow access.


You now will be using LDAP authentication.

## This REQUIRES the PHP LDAP module to be installed. ##