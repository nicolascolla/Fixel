# Fixel

![](Fixel.png)

Fixel is a simple Ubuntu Touch app to fix stuck pixels. It is a fork of [Inglebard's original](https://github.com/Inglebard/Fixel) packaged for newer UT versions. Some additional features (like dark mode support) might be added in the future.

[![OpenStore](https://open-store.io/badges/en_US.png)](https://open-store.io/app/fixel.collaproductions)
[![](https://i.imgur.com/KIipzE8.png)](https://t.me/collaproductions)

### Building the app (Ubuntu-based distros)

Install [clickable](https://clickable-ut.dev/en/latest/install.html):

```
$ sudo add-apt-repository ppa:bhdouglass/clickable
$ sudo apt-get install clickable
```

Clone this repository and build:

```
$ git clone https://github.com/nicolascolla/Fixel.git
$ cd Fixel
$ clickable
```

The resulting click package will be found under build/all/app.
