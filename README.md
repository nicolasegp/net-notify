# net-notify

<img src="https://img.shields.io/badge/Versi%C3%B3n-v2.3-blue.svg">

Mini-Proyecto para notificar cuando llegue el Internet a un equipo mediante el uso de la Terminal y Telegram.

> Hilo en Reddit: [Bash Scripting: Notificar que llego Internet](https://www.reddit.com/r/vzla/comments/brqio0/bash_scripting_notificar_que_llego_internet/)

## Instalación

```bash
sudo curl -L https://git.io/fjRs1 -o /usr/local/bin/net-notify
sudo chmod a+rx /usr/local/bin/net-notify
```

#### Modificar Token y Chat

```bash
sudo nano /usr/local/bin/net-notify
```

Modificar las variables **TOKEN** _(de su Bot)_ y **CHAT** _(de su cuenta de telegram, grupo o canal)_

## Uso

Una vez no tengamos internet podemos ejecutar el comando `net-notify` y minimizar la terminal, la idea del script es que nos llegue un mensaje en Telegram apenas el equipo se conecte a internet.

## Modificaciones

#### v2.3

* Cambiado número de intentos por tiempo transcurrido

#### v2

* Eliminada la dependencia [telegram.sh](https://github.com/fabianonline/telegram.sh)

#### v1

* El usuario [u/knvngy](https://www.reddit.com/user/knvngy/) dio la recomendación de editar la misma linea con los intentos para asi evitar un log muy largo y saturara de información la terminal.

## Capturas

#### Terminal

<img src="https://raw.githubusercontent.com/nicolasegp/net-notify/master/img/001.png">

#### Telegram

<img src="https://raw.githubusercontent.com/nicolasegp/net-notify/master/img/002.png" height="500">
