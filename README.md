# Rasbperry Pi Snippets

## Create user

```sh
sudo adduser --disabled-password --gecos "" USER_NAME
```

## Add user to group

```sh
sudo adduser USER_NAME GROUP
```

## Temperature

```sh
vcgencmd measure_temp
```
