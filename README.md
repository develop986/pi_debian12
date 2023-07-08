# pi_debian12

> [How to Install Debian 12 Bookworm on Raspberry Pi (2023 update) – RaspberryTips](https://raspberrytips.com/install-debian-on-raspberry-pi)

## 日本語環境設定

```
$ sudo apt -y install task-japanese locales-all
$ sudo dpkg-reconfigure locales
$ sudo apt -y install task-japanese-desktop ibus-kkc
$ sudo apt -y install fonts-noto-cjk fonts-noto-cjk-extra
$ sudo dpkg-reconfigure tzdata
$ sudo reboot
```

## デフォルトエディタ変更

```
$ sudo update-alternatives --config x-terminal-emulator
$ sudo update-alternatives --config editor
```

## ZIP

```
$ sudo apt -y install zip unzip
```

## Curl

```
$ sudo apt -y install curl
```

## グラフィックス関係ソフト

```
$ sudo apt -y install gimp-plugin-registry gmic gimp-gmic inkscape dia
```


