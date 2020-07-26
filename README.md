### # Install Genymotion

```
$ sudo apt-get update

$ sudo apt-get install virtualbox

# download genymotion
$ ls -l ~/Downloads/ | grep geny

$ chmod +x  genymotion...xxx.bin

$ sudo ~/Downloads/genymotion...xxx.bin
```

<hr>

### # Install Nginx

```
$ sudo apt-get update

$ sudo apt-get install nginx
```

<hr>

### # Install Apache

```

```

<hr>

### # Install PHP

```
# Nginx
$ sudo apt-get install php-fpm

# another version of PHP
$ sudo apt-get install software-properties-common
$ sudo add-apt-repository ppa:ondrej/php
$ sudo apt-get update
$ sudo apt-get install php7.3-fpm
```

<hr>

### # Change PHP Version

```
$ sudo update-alternatives --config php
```

<hr>

### # Install phpMyAdmin

```
$ sudo apt-get update

$ sudo apt-get install phpmyadmin

$ sudo ln -s /usr/share/phpmyadmin /var/www/html/phpmyadmin
```

<hr>

### # Install NodeJS

```
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -

$ sudo apt-get install -y nodejs
```

<hr>

### # Install Yarn

```
$ curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

$ sudo apt-get update && sudo apt-get install yarn
```

<hr>

### # Install Deno

```
$ curl -fsSL https://deno.land/x/install/install.sh | sh
```

<hr>

### # Install FLutter

```
$ sudo snap install flutter --classic

$ flutter doctor
```

<hr>

### # Add Android Studio to the Dash

- Open Android Studio
- Configure -> Create Desktop Entry

<hr>

### # Install Java

```
$ sudo apt install default-jre

$ sudo apt install default-jdk
```

### # Fix "/usr/bin/env: ‘bash\r’: No such file or directory"

```
$ sudo apt-get install -y dos2unix # Installs dos2unix Linux
$ sudo find . -type f -exec dos2unix {} \; # recursively removes windows related stuff
```

### # Install MPC-HC

```
$ sudo snap install mpc-hc --edge
```

### # Nginx enable PHP

```
location ~\.php$ {
  include snippets/fastcgi-php.conf;
  fastcgi_pass unix:/run/php/php7.3-fpm.sock;
  fastcgi_param SCRIPT_FILENAME $document_root/$fastcgi_script_name;
}
```
