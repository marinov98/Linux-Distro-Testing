# Purpose
- In case I go to a new machine I know what to install immediately

# Table of Contents
1. [MacOS](#MacOs)
2. [Ubuntu](#Ubuntu)
3. [Arch-based distros](#Arch-based)

### Good Fonts For Programming
- Fira Code (New personal favorite)
- Hack (old Personal Favorite)
- Source Code Pro
- Inconsolata

# Tiling managers and terminal multiplexers
- i3wn
- tmux
- iTerm(mac only)

### Pip (For Python developement)
  - Rope: ```sudo pip install rope``` 
  - Jedi: ```sudo pip install jedi``` 
  - flake: ```sudo pip install flake8``` 
  - autopep: ```sudo pip install autopep8```  
  - yapf: ```sudo pip install yapf``` 
  - pygments : ```sudo pip install pygments```
  - virtualenv & virtualenvwrapper: ```sudo pip install virtualenv virtualenvwrapper```
  - powerline shell: ```sudo pip install powerline-shell```
  
### Extensions for vs code: 
- ```Auto Close Tag```
- ```Auto Rename Tag```
- ```Color Highlight```
- ```Project manager```
- ```Paste and Indent```
- ```Path Intellisense```
- ```Prettier```
- ```Bracket pair colorizer```
- ```vim```
- ```C++ && Clang Adapter```
- ```clang format```
- ```Python```
- ```JavaScript```
- ```gitlenns```
- ```Chrome debugger```
- ```Bookmarks```
- ```(git)project manager```
- ```Live Share```
- ```Beautify```
- ```code runner```
- ```Angluar 8 Snippets```
- ```live server```
- ```react,redux... snippets```(this one is long but very recognizable)
  
  
### Npm
- tern: ```sudo npm install -g tern```
- eslint: ```npm install eslint```
- react ```sudo npm install -g create-react-app```
- reactstrap
- bootstrap
- typscript, tslint
- web
  
## MacOS

### useful apps
- snaptool 
- thought train
- there (time zones)
- deskcover
- bartender (hiding)
- padbury clock 

### Necesities
- [brew](https://brew.sh/)
- curl:
  - ```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null```
  - ```brew install curl```
- cask: ```brew install cask```
- Ranger: ```brew install ranger```
- nnn: ```brew install nnn```
- tmux: ``` brew install tmux```

### Programming
- pip: ```brew install pip```
- Xcode setpaths: ```xcode-select --install```
- llvm: ```brew install --with-toolchain llvm```
- clang-format: ```brew install clang-format```
- ctags ```brew install ctags```
- gdb ```brew install gdb```
- npm: ```brew install npm```
- node: ```brew install node```

### Keyboard Configuration
Karabiner: ```brew cask install karabiner karabiner-elements```

### Latex
- ```brew tap caskroom/cask```
- ```brew cask install mactex```

### Emacs and Vim
- emacs:
  - ```brew tap d12frosted/emacs-plus```
  - ```brew install emacs-plus```
- Vim:
  - ```brew install vim && brew install macvim```
  - ```brew link macvim```
    
### Zshell
- ```brew install zsh zsh-completions```


## Ubuntu

### Commands
- ```apt-get``` can be replaced with ```apt```
- Install Command ```sudo apt-get install [package-name]```
- Delete Command ```sudo apt-get remove [package-name]```
- Update Command ```sudo apt-get upgrade [package-name]```

### Necesities
- Curl ```sudo apt install curl```
- cask ```curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python```
- Git 
  - ```sudo apt install git```
  - ```git config --global user.name "Your Name"```
  - ```git config --global user.email "youremail@domain.com"```
- GDB (debugger) ```sudo apt-get install gdb```
- net-tools ```sudo apt-get install net-tools```

### Keyboard configuration
- tweak tool (ubuntu) ```sudo add-apt-repository universe``` ```sudo apt install gnome-tweak-tool```
- xcape ```sudo apt install xcape```
  - Make caps lock esc & control: ```xcape -e 'Control_L=Escape'``` or  
  - ```xcape -e '#66=Escape``` if the first command didnt work
- Add correct command to ```.profile```

### Programming 
- build-essential ```sudo apt-get install build-essential```
- Gcc ```sudo-apt-get install gcc```
- Clang ```sudo apt-get install clang```
- LibClang ```sudo apt-get install libclang-dev```
- llvm ```sudo apt-get install lldb```
- ctags ```sudo apt-get install ctags```
- ncurses ```sudo apt-get install libncurses5-dev libncursesw5-dev```
- cmake ```sudo apt-get install cmake```
- ranger: ```sudo apt-get install ranger```
- nnn: ```sudoapt-get install nnn```
- clang-format ```sudo apt-get install clang-format```
- Python
  - ```sudo apt-get install python-pip```
  - ```sudo apt-get install virtualenv``` && ```sudo pip install virtualenv``` 
- **LATEX** ```sudo apt-get install texlive-full``` & ```sudo apt install gummi```
- Web dev tools
  - npm (look up)
  - react
  
## Editors 
- Gummi text editor (Latex text editor as backup to emac's auctex) ```sudo apt install gummi```
-  vs code (backup in case new language is used) ```sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make```
  - ```sudo apt-get update```
  - ```sudo apt-get install ubuntu-make```
  - ```umake web visual-studio-code```
- Emacs ```sudo apt-get install emacs26 auctex ```

## Battery Management
- ```sudo apt install tlp``` &```sudo apt install tlpui```

### Mundane
- Spotify
  - ```sudo apt-get install snapd```
  - ```sudo snap install spotify```
- Chromium-browser ```sudo apt install -y chromium-browser```
- Skype

### Gaming
- ```wget -nc https://dl.winehq.org/wine-builds/Release.key ```
- ```sudo apt-key add Release.key```
- ```sudo apt-add-repository 'https://dl.winehq.org/wine-builds/ubuntu/' ```
- ``` sudo apt update ```
- ``` sudo apt install --install-recommends winehq-staging```
- ``` sudo apt install winetricks ```

### Zshell
- ```sudo apt-get install zsh```

### i3wn
- ```sudo apt install i3```

### i3-gaps
- https://benjames.io/2017/09/03/installing-i3-gaps-on-ubuntu-16-04/ this also works on 18.04

### Trash cli
- ``` sudo apt install trash-cli``` (trash-empty command to empty trash from terminal)

### feh
- ```sudo apt install feh```

### lxappearance & awesone fonts
- ``` sudo apt install lxappearance fonts-font-awesome```

### xrandr and arandr
- ```sudo apt install xrandr arandr```

### neofetch
- ```sudo apt install neofetch```

## Arch-based

### Commands
- Install Command ``` sudo pacman -S [package-name] ```
- Delete Command ``` sudo pacman -R [package-name]```
- Update ``` sudo pacman -Sy ```

### Fonts
- Hack: ``` sudo pacman -S ttf-hack ```
- Source Code Pro: ``` sudo pacman -S adobe-source-code-pro-fonts ```

### neofetch
- ```sudo pacman -S neofetch```

####  General Programming
-  ``` sudo pacman -S git ```
- ``` sudo pacman -S gdb ```
- ``` sudo pacman -S curl ```
- ``` sudo pacman -S ranger ```
- ```sudo pacman -S nnn```
#### Keyboard configuration
- On Gnome: ```sudo pacman -S gnome-tweak-tool```
- General: ```sudo pacman -S xorg-xmodmap```
- Graphical front end: ```sudo pacman -S xkeycaps```
- Caps2esc: ```sudo pacman -S interception-caps2esc```
- in ```/etc/udevmon.yaml``` add:
``` yaml
- JOB: "intercept -g $DEVNODE | caps2esc | uinput -d $DEVNODE"
  DEVICE:
    EVENTS:
      EV_KEY: [KEY_CAPSLOCK, KEY_ESC]
 ```
- Finally, ```sudo systemctl enable udevmon```
#### C/C++
- ``` sudo pacman -S base-devel ```
- ``` sudo pacman -S clang ```
- ``` sudp pacman -S cmake ```
- ``` sudo pacman -S llvm ```
- ``` sudo pacman -S lldb ```
- ``` sudo pacman -S ctags ```
- ``` sudo pacman -S clang-format```
#### Python
- ``` sudo pacman -S python3 ```
- ``` sudo pacman -S python-pip ```
- ``` sudo pacman -S pyenv ```
#### Javascript
- ``` sudo pacman -S nodejs ```
- ``` sudo pacman -S npm ```

### Browsing, neftlix & Video Player
- ``` sudo pacman -S google-chrome ```
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

### Zshell
- ```sudo pacman -S zsh```

### Feh
- ```sudo pacman -S feh```
