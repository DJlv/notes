* sudo pacman -Syy
* sudo pacman -S vim
* sudo vim /etc/pacman.conf
* [archlinuxcn]  
  SigLevel = Optional TrustedOnly  
  Server = https://mirrors.ustc.edu.cn/archlinuxcn/$arch  
  Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch  
*  sudo pacman -S archlinuxcn-keyring  
* sudo pacman -S antergos-keyring
* sudo pacman -Syu
* sudo pacman -S yaourt
#安装环境
* sudo pacman -S base-devel
* sudo pacman -S google-chrome
* yaourt -S  fcitx-configtool fcitx-im
* sudo vim /etc/environment
    - GTK_IM_MODULE=fcitx
    - QT_IM_MODULE=fcitx
    - XMODIFIERS="@im=fcitx"
