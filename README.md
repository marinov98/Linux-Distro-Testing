# Purpose
- In case I go to a new machine I know what to install immediately

# Table of Contents
1. [MacOS](#MacOs)
2. [Ubuntu](#Ubuntu)
3. [Antergos-Arch](#Antergos-Arch)

### Good Fonts For Programming
- Hack (Personal Favorite)
- Source Code Pro
- Inconsolata

### Pip
  - Rope: ```pip install rope``` 
  - Jedi: ```pip install jedi``` 
  - flake: ```pip install flake8``` 
  - autopep: ```pip install autopep8```  
  - yapf: ```pip install yapf``` 
  - pygments : ```pip install pygments```
  - virtualenv & virtualenvwrapper: ```pip install virtualenv virtualenvwrapper```
  
## MacOS

## Ubuntu

### Fonts
- Ubuntu font book

### Commands
- Install Command ``` sudo apt-get install [package-name] ```
- Delete Command ``` sudo apt-get remove [package-name]```
- Update Command ``` sudo apt-get upgrade [package-name] ```

### Necesities
- Curl ```sudo apt install curl```
- cask ```curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python```
- Git 
1. ```sudo apt install git```
2. ```git config --global user.name "Your Name"```
3. ```git config --global user.email "youremail@domain.com"```
- GDB (debugger) ```sudo apt-get install gdb```
- tweak tool (ubuntu) ```sudo add-apt-repository universe``` ```sudo apt install gnome-tweak-tool```
- ivy (look up)
### Programming 
- Gcc ```sudo-apt get install gcc```
- Clang ```sudo apt-get install clang```
- LibClang ```sudo apt-get install libclang-dev```
- llvm ```sudo apt-get install lldb```
- ctags ```sudo apt-get install ctags```
- cmake ```sudo apt-get install cmake```
- Python
- - ```sudo apt-get install python-pip```
- - ```sudo apt-get install virtualenv``` && ```sudo pip install virtualenv``` 
- **LATEX** ```sudo apt-get install texlive-full```
- Web dev tools
- - npm (look up)
- - react
## Editors 
- Gummi text editor (Latex text editor as backup to emac's auctex) ```sudo apt install gummi```
-  vs code (backup in case new language is used) ```sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make```
- - ```sudo apt-get update```
- - ```sudo apt-get install ubuntu-make```
- - ```umake web visual-studio-code```
- Extensions for vs code: 
- - ```Auto Close Tag```
- - ```Auto Rename Tag```
- - ```Color Highlight```
- - ```Project manager```
- - ```Paste and Indent```
- - ```Path Intellisense```
- - ```Prettier```
- Emacs ```sudo apt-get install emacs26 auctex ```
### Mundane
- Spotify
- - ```sudo apt-get install snapd```
- - ```sudo snap install spotify```
- Chromium-browser ```sudo apt install -y chromium-browser```
- Skype
- Ranger (preinstalled on ubuntu) 

### Gaming
- ```wget -nc https://dl.winehq.org/wine-builds/Release.key ```
- ```sudo apt-key add Release.key```
- ```sudo apt-add-repository 'https://dl.winehq.org/wine-builds/ubuntu/' ```
- ``` sudo apt update ```
- ``` sudo apt install --install-recommends winehq-staging```
- ``` sudo apt install winetricks ```


## Antergos-Arch

### Fonts
- Hack: ``` sudo pacman -S ttf-hack ```
- Source Code Pro: ``` sudo pacman -S adobe-source-code-pro-fonts ```

### Commands
- Install Command ``` sudo pacman -S [package-name] ```
- Delete Command ``` sudo pacman -R [package-name]```
- Update ``` sudo pacman -Sy ```

####  General Programming
-  ``` sudo pacman -S git ```
- ``` sudo pacman -S gdb ```
- ``` sudo pacman -S curl ```
- ``` sudo pacman -S ranger ```
#### Keyboard configuration
- On Gnome: ```sudo pacman -S gnome-tweak-tool```
- General: ```sudo pacman -S xorg-xmodmap```
- Graphical front end: ```sudo pacman -S xkeycaps```
#### C/C++
- ``` sudo pacman -S base-devel ```
- ``` sudo pacman -S clang ```
- ``` sudp pacman -S cmake ```
- ``` sudo pacman -S llvm ```
- ``` sudo pacman -S lldb ```
- ``` sudo pacman -S ctags ```
#### Python
- ``` sudo pacman -S python3 ```
- ``` sudo pacman -S python-pip ```
- ``` sudo pacman -S pyenv ```
#### Javascript
- ``` sudo pacman -S nodejs ```
- ``` sudo pacman -S npm ```

### Browsing, neftlix & Video Player
- ``` sudo packman -S google-chrome ```
-  ``` sudo pacman -S chrome-widevine ```
-  ``` sudo pacman -S pepper-flash ```
- ``` sudo pacman -S vlc ```
### Emacs
- emacs ``` sudo pacman -S emacs```
- auctex ``` sudo pacman -S auctex```
- cask ```curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python```
### Gaming 
- ```sudo pacman -S wine-staging winetricks```
- ```sudo pacman -S giflib lib32-giflib libpng lib32-libpng libldap lib32-libldap gnutls lib32-gnutls mpg123 lib32-mpg123 openal lib32-openal v4l-utils lib32-v4l-utils libpulse lib32-libpulse alsa-plugins lib32-alsa-plugins alsa-lib lib32-alsa-lib libjpeg-turbo lib32-libjpeg-turbo libxcomposite lib32-libxcomposite libxinerama lib32-libxinerama ncurses lib32-ncurses opencl-icd-loader lib32-opencl-icd-loader libxslt lib32-libxslt libva lib32-libva gtk3 lib32-gtk3 gst-plugins-base-libs lib32-gst-plugins-base-libs vulkan-icd-loader lib32-vulkan-icd-loader cups samba dosbox ```
