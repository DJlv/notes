# manjaro安装
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
**********
# plug
* sudo pacman -S curl
* curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

***********
# 报错 curl: (7) Failed to connect to raw.githubusercontent.com port 443: Connection refused
* 修改hosts  
  sudo vim /etc/hosts  
  添加如下内容：  
  199.232.68.133 raw.githubusercontent.com
  
>> Plot[Sin[x],{x,0,10}]
```c
```

https://app.diagrams.net/
http://www.fooplot.com/
