<div>
  <h1 align="center">Melody</h1>
  <h3 align="center"><img src="data/icons/com.github.artemanufrij.playmymusic.svg"/><br>A music player for listening to local music files, online radios, and Audio CD's</h3>
  <p align="center">Designed for <a href="https://elementary.io">elementary OS</a></p>
</div>

### Donate
<a href="https://www.paypal.me/ArtemAnufrij">PayPal</a> | <a href="https://liberapay.com/Artem/donate">LiberaPay</a> | <a href="https://www.patreon.com/ArtemAnufrij">Patreon</a>

<p align="center">
  <a href="https://appcenter.elementary.io/com.github.artemanufrij.playmymusic">
    <img src="https://appcenter.elementary.io/badge.svg" alt="Get it on AppCenter">
  </a>
</p>

<br/>

![screenshot](screenshots/Screenshot.png)
![screenshot](screenshots/Screenshot_Artists.png)
![screenshot](screenshots/Screenshot_Tracks.png)

## Install from Github.

As first you need elementary SDK
```
sudo apt install elementary-sdk
```

Install dependencies
```
sudo apt install libsoup2.4-dev libsqlite3-dev libgstreamer-plugins-base1.0-dev libtagc0-dev
```

Clone repository and change directory
```
git clone https://github.com/artemanufrij/playmymusic.git
cd playmymusic
```

Compile, install and start Play My Music on your system
```
meson build --prefix=/usr
cd build
sudo ninja install
com.github.artemanufrij.playmymusic
```
