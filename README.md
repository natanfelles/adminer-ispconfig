# Adminer Ispconfig Plugin

Authenticate and auto-check host by ISPConfig Remote API

Your ISPConfig Remote User needs the following functions:
* Sites database functions
* Server functions

Edit the objects of AdminerISPConfig.php file with your credentials:

```php
var $username = 'admin';
var $password = 'admin';
var $soap_uri = 'https://server.domain.tld:8080/remote/';
var $check_ssl = FALSE; // Set FALSE if you are using a Self Signed certificate
```

### More info:
* https://natanfelles.github.io/
* http://www.ispconfig.org/
* http://www.adminer.org/plugins/#use
