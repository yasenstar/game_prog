# How to install Roblox Studio in Ubunut

Reference link: [Linux Made Simple](https://www.linuxmadesimple.info/2020/08/how-to-install-roblox-studio-on-ubuntu.html)

Using Wine with commands below:

```bash
sudo dpkg --add-architecture i386
wget -nc https://dl.winehq.org/wine-builds/winehq.key
sudo apt-key add winehq.key
sudo add-apt-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ focal main'
sudo apt update
sudo apt install --install-recommends winehq-stable
winecfg
```

Download Roblox Studio:

[https://www.roblox.com/Create](https://www.roblox.com/Create)

Commands are based on this:

[https://wiki.winehq.org/Ubuntu](https://wiki.winehq.org/Ubuntu)

Click the EXE file and install the Studio

Enjoy!