# net-notify

Mini-Proyecto para notificar cuando llegue el Internet a un equipo mediante el uso de la terminal.

Hilo en reddit: https://www.reddit.com/r/vzla/comments/brqio0/bash_scripting_notificar_que_llego_internet/

## Requerimientos

* El proyecto usa [telegram.sh](https://github.com/fabianonline/telegram.sh) (Agregado en esto repositorio)

## Instalación

#### Para telegram.sh

```bash
sudo curl -L https://raw.githubusercontent.com/nicolasegp/net-notify/master/telegram -o /usr/local/bin/telegram
sudo chmod a+rx /usr/local/bin/telegram
```

#### Para net-notify

```bash
sudo curl -L https://raw.githubusercontent.com/nicolasegp/net-notify/master/net-notify -o /usr/local/bin/net-notify
sudo chmod a+rx /usr/local/bin/net-notify
```

#### Modificar Token y Chat

```bash
sudo nano /usr/local/bin/net-notify
```

Modificar las variables **TOKEN** _(de su Bot)_ y **CHAT** _(de su cuenta de telegram)_

## Modificaciones

* El usuario [u/knvngy](https://www.reddit.com/user/knvngy/) dio la recomendación de editar la misma linea con los intentos para asi evitar un log muy largo y saturara de información la terminal.

## Capturas

#### Terminal

<img src="https://raw.githubusercontent.com/nicolasegp/net-notify/master/img/001.png">

#### Telegram

<img src="https://raw.githubusercontent.com/nicolasegp/net-notify/master/img/002.png" height="500">
