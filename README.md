# install-chrome-archlinux
### Tutorial para instalação do Google Chrome no Arch Linux
---
<img src="/imagens/chrome.png" width="500px"/>

1) No terminal do Arch Linux Kde ou Gnome, acessar a pasta _Dowloads_ digitando:</br>
```sh
cd Downloads
```
 - No terminal do Arch Linux Cinnamon, acessar a pasta _Desktop_ digitando:</br>
 ```sh
 cd Desktop
```

2) Instalar o git, wget e curl utilizando o comando:</br>
```sh
sudo pacman -S git wget curl
```

3) Clonar o repositório do _google-chrome_ disponível na **AUR** usando o comando:</br>
```sh
git clone http://aur.archlinux.org/google-chrome.git
```

4) Acessar o diretório _google-chrome_ que foi criado após o comando acima:</br>
```sh
cd google-chrome
```

5) Digitar os comandos a seguir:</br>
```
sudo pacman -Sy --needed base-devel git
makepkg -si
```
6) Após os comandos acima o Google Chrome estará instalado podendo ser acessado através da interface gráfica ou através do terminal, neste caso digitando-se:</br>
```sh
google-chrome-stable
```
