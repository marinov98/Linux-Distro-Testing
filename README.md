# Linux-Distro-Testing
- Things I might want to install when switching distros going to a new machine 

### Good Fonts For Programming
- Hack (Personal Favorite)
- Source Code Pro
- Inconsolata

## Ubuntu (Debian)

### Commands
- Install Command ``` sudo apt-get install [package-name] ```
- Delete Command ``` sudo apt-get remove [package-name]```

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
- - Rope: ```pip install rope``` 
- - Jedi: ```pip install jedi``` 
- - flake: ```pip install flake8``` 
- - autopep: ```pip install autopep8```  
- - yapf: ```pip install yapf``` 
- - pygments : ```pip install pygments```
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



## Antergos (Arch)

### Commands
- Install Command ``` sudo pacman -S [package-name] ```
- Delete Command ``` sudo pacman -R [package-name]```

####  General Programming
-  ``` sudo pacman -S git ```
- ``` sudo pacman -S gdb ```
- ``` sudo pacman -S curl ```
- ``` sudo pacman -S ranger ```
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

### Browsing and neftlix
- ``` sudo packman -S google-chrome ```
-  ``` sudo pacman -S chrome-widevine ```
-  ``` sudo pacman -S pepper-flash ```


### Emacs
- emacs ``` sudo pacman -S emacs```
- auctex ``` sudo pacman -S auctex```
- cask ```curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python```
