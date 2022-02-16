# KCal

https://github.com/kcal-app/kcal

## Manual

```shell

$ sudo apt-get install software-properties-common
$ sudo add-apt-repository ppa:ondrej/php
$ sudo apt-get update
$ sudo apt-get install elasticsearch mysql-server-8.0 nginx-full php8.0 php8.0-bcmath php8.0-cli php8.0-curl php8.0-gd php8.0-intl php8.0-mbstring php8.0-mysql php8.0-redis php8.0-xml php8.0-zip redis php8.0-fpm
$ curl -s https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin/ --filename=composer
$ cd /var/www
$ sudo mkdir kcal
$ sudo chown $USER:`id -gn $USER` kcal
$ cd kcal
$ git clone https://github.com/kcal-app/kcal.git .


```