# Hextris



## Manual

This installation method will use a standard centos based virtual machine.

First to get this static website running we need a webserver that our browser can talk to. A very common webserver is Apache HTTPD ( https://httpd.apache.org/ ), to install httpd we run:

```shell
git@github.com:CSSE6400/selfhost-cookbook.git
$ sudo yum install httpd
$ sudo systemctl enable httpd
$ sudo systemctl start httpd
```

This installation comes with a default config that will host files stored in `/var/www/html`. This is where we should place the Hextris games files. TO get these files on the server we are going to cheat and install git to clone the repo on the box.

```
Note: Its not recommended to deploy software this way. It can lead to long term security issues.
```

To install git run:

```shell
$ sudo yum install git
```

Lets move into the default file serving location.

```shell
$ cd /var/www/html
```

Finally we can deploy the hextris files.

```shell
sudo git clone https://github.com/Hextris/hextris .
```

// todo(eh): Shouldnt this fail from file permission issues.

## Container ( Week 4+ )


## Terraform ( Week 6+ )