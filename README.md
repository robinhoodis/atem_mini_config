AV-raspi-config - A/V Software Installer
=========================================

### bitfocus.io Companion, Video Playout, Background images, Sound Effects and Music players.

Automate the deployment of all the audio and video software for your Raspberry PI4.

This is the software dependency for AV-companion-atem Scene switching content repo.

## Prerequisites

#### Raspberry Pi4 with 4GB or 8GB of RAM connected to a network with access to the internet
#### Operating System [installed](https://www.raspberrypi.org/documentation/installation/installing-images/README.md).
#### Tested Working
* 32 bit Raspbian LITE and Full
* 64 Bit Raspbian Buster
* Ubuntu 20.04
* Ubuntu-Mate 18.0.4
#### Not Working
* LibreElec

## Installing

Run the following three commands on your raspberry PI4 and follow prompts.
 
```console

sudo apt-get -y install ansible

curl -O https://raw.githubusercontent.com/robinmordasiewicz/AV-raspi-config/master/raspi-config.yml

ansible-playbook raspi-config.yml


```

![](https://github.com/robinmordasiewicz/terminalizer/raw/master/AV-raspi-config.gif)

## Contents

* [Bitfocus.io Companion](https://bitfocus.io/) - [Companion Facebook group](https://www.facebook.com/groups/2047850215433318/)
* omxplayer
* omxd
* imagemagick
* mpd
* mpc


https://robinmordasiewicz.github.io/AV-raspi-config/

<script src="https://utteranc.es/client.js" repo="robinmordasiewicz/AV-raspi-config" issue-term="pathname" theme="github-light" crossorigin="anonymous" async></script>
