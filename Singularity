Bootstrap: docker
From: archlinux:latest
#####Also note, the newer that is used, the greater the chance of compatability problems w/ older kernels

%labels
MAINTAINER TRF

%files

%environment
    
%post
    echo "Installing tmsu via yet another yaourt..."
    pacman -Sy git
    git clone https://aur.archlinux.org/yay.git
    cd yay
    makepkg -si
    yay -S tmsu
