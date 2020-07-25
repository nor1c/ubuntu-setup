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

<hr>

### # Install Apache

<hr>

### # Install PHP

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
