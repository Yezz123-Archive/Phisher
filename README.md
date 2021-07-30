![Header](.github/header.svg)

<p align="center">
   <img src="https://img.shields.io/badge/Dev-Yezz123-green?style"/>
   <img src="https://img.shields.io/github/license/yezz123/phisher"/>
   <img src="https://img.shields.io/github/stars/yezz123/phisher"/>
   <img src="https://img.shields.io/github/forks/yezz123/phisher"/>
   <img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99" alt="Star Badge"/>
   <img src="https://visitor-badge.laobi.icu/badge?page_id=yezz123.Pretty-Readme">
</p>

# Phisher

- Tool designed for performing various social engineering attacks using PHP Apache & Ngrok.

## Getting Started

- For phishing, Phisher allows for sending phishing Website to get the Number | Email | Username & password, as well as some more advanced options, such as Original Template, and fast phish connection with Ngrok.

### Prerequisites

- Linux environment (Ubuntu, Debian, CentOS, RedHat, Fedora, etc.).
- PHP 5.6+, Apache 2.4+.
- Curl, OpenSSL.

### Project setup

```sh
# clone the repo
$ git clone https://github.com/yezz123/Phisher

# move to the project folder
$ cd Phisher
```

### Install dependencies

- Install all the dependencies used to run Phisher (PHP, Apache, Ngrok, Curl, OpenSSL).

1- Install PHP.

```shell
# install all php deps
$ sudo apt install php libapache2-mod-php

# Once the packages are installed restart the Apache service
$ sudo systemctl restart apache2
```

2- Install Wget.

```shell
# login via SSH as root and run the command
$ sudo apt-get install wget

# confirm the installation of the wget
$ sudo dpkg -l | grep wget
```

3- Install UnZip & Curl.

```shell
# Ubuntu or Debian use the command below to install unzip
$ sudo apt-get install unzip

# get latest stable curl version
$ sudo apt install curl
```

### Running the Application

- After the dependencies are installed, you can run the application by running the following command.

```sh
# Running the application
$ bash Phisher.sh
```

> - If the link don't show run the **NGROK Stat** using this ling <http://localhost:4040/status>.

## Preconfigured Packages

Includes preconfigured packages to kick start Phisher by just setting appropriate configuration.

| Package                     |Usage         |
| --------------------------- | ----------------------------------------------------------------- |
| [NGROK](https://ngrok.com/) | cross-platform application that enables developers to expose a local development server to the Internet with minimal effort. |

## Contributing

- Join the Phisher Creator and Contribute to the Project if you have any enhancement or add-ons to create a good and Secure Project, Help any User to Use it in a good and simple way.

### Disclaimer

This project can only be used for educational purposes. Using this software against target systems without prior permission is illegal, and any damages from misuse of this software will not be the responsibility of the author.

## License

This project is licensed under the terms of the [MIT license](LICENSE).
