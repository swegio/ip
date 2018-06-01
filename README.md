# Simple IP Address Reporting
```PHP
<?php echo $_SERVER["REMOTE_ADDR"]."\n"; ?>
```

## Pre-requisites
- Webserver:
    - PHP
    - cURL
- Client:
    - cURL

## Getting started

- Clone or [download](https://github.com/swegio/ip/archive/master.zip) the repository into your local directory of choice

- Upload the file `index.php` to your webserver

>**or** if you prefer building through console access to your host:
>
>`$ echo "<?php echo \$_SERVER[\"REMOTE_ADDR\"].\"\\n\"; ?>" >> index.php`

- Open up your console, use cURL to display IP address:
```console
$ curl yourserver.com
8.8.8.8
```

>Depending on your webserver configuration you may be required to include "/index.php" like:

```console
$ curl yourserver.com/index.php
8.8.8.8
```