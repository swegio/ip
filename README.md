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

- Clone the repository into your project directory of choice
```console
$ git clone git@github.com:jaechow/ip.git
```

- Upload the file to your host

>**or** if you prefer building through console access to your host:
>
>`$ echo "<?php echo \$_SERVER[\"REMOTE_ADDR\"].\"\\n\"; ?>" >> index.php`

- Open up console, here's the cURL:
```console
$ curl yourserver.com
8.8.8.8
```

>Depending on your webserver configuration you may be required to include "/index.php" like:

```console
$ curl yourserver.com/index.php
8.8.8.8
```