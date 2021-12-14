<p align="center">
    <img src="https://repository-images.githubusercontent.com/123972919/05e941e3-a69e-4260-be4e-4386749d4de6" width="320" />
</p>

![Watchers](https://img.shields.io/github/watchers/swegio/ip.svg)
![Stars](https://img.shields.io/github/stars/swegio/ip)
![Commits](https://img.shields.io/github/commit-activity/m/swegio/ip/main)
![Last Commit](https://img.shields.io/github/last-commit/swegio/ip/main)
[![GitHub Issues](https://img.shields.io/github/issues/swegio/ip.svg)](https://github.com/swegio/ip/issues)
<a href="https://discord.com/channels/840764739264839690/841418043510751242"><img src="https://img.shields.io/discord/840764739264839690" /></a>

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

>**or** if you prefer to use your terminal emulator of choice:
>
>`$ echo "<?php echo \$_SERVER[\"REMOTE_ADDR\"].\"\\n\"; ?>" >> index.php`

- Open up your console, type `curl` then replace 'yourserver.com' with the location of your `index.php` to render the page and display your IP address:

```console
foo@bar:~$ curl yourserver.com
8.8.8.8
```

>Depending on your webserver configuration you may be required to include "/index.php" like:

```console
foo@bar:~$ curl yourserver.com/index.php
8.8.8.8
```