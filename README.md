# Simple IP Address Reporting
```PHP
<?php echo $_SERVER["REMOTE_ADDR"]."\n"; ?>
```

## Pre-requisites
1. Server to handle PHP
2. cURL console access

## Getting started

1. Clone the repository into your project directory of choice
```console
$ git clone git@github.com:jaechow/ip.git
```

2. Upload the file to your host

>**or** if you prefer building through console access to your host:
>`$ echo "<?php echo $_SERVER[\"REMOTE_ADDR\"].\"\\n\"; ?>" >> index.php`

3. Open up console, here's the cURL:
```console
$ curl *your-index.php-location*
*your-ip-address-appears-below*
```
