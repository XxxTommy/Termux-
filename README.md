# Termux-指令套件安裝程序記錄
Termux 相關指令等等

打開 Termux 並輸入
Termux儲存空間權限指令

$termux-setup-storage 

大補帖安裝方法

$pkg update -y && pkg upgrade -y && pkg install wget && pkg install curl openssh -y && pkg install git man -y && pkg install python && pkg install python2 zip && pkg install php -y && apt install zsh && apt install vim -y

---------------

$pkg install proot -y

$termux-chroot


-----------------

手機 Kali nethunter
預先下載軟件下載對應的壓縮包安裝

$termux-setup-storage

$pkg install wget

$wget -O install-nethunter-termux https://offs.ec/2MceZWr

$chmod +x install-nethunter-termux

$cd storage/shared/Download

$mv kalifs-arm64-full.tar.xz /data/data/com.termux/files/home

$cd /data/data/com.termux/files/home

$./install-nethunter-termux

--------------

$pkg install vim

$pkg install vim-python

vim:
文字編輯器。
進入後按 i 進入輸入模式，
按 esc 離開輸入模式，
:wq 存檔後離開，
:q 直接離開

---------

$pkg install tsu -y

$tsu

--------------
ubuntu....

$pkg install proot-distro

$proot-distro list

$proot-distro install ubuntu

$proot-distro login ubuntu

------------



