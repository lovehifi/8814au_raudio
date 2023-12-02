# Build driver 8814au for rAudio


```
sudo pacman -Syu
```
>
>
:: Proceed with installation? [Y/n] n
> **n**
>
> sudo mv -f /usr/lib/modules/6.1.64-2-rpi-ARCH/build /usr/lib/modules/6.1.58-2-rpi-ARCH/
>
> sudo pacman -S linux-rpi-headers
>
:: Proceed with installation? [Y/n]
> y
> 
> sudo pacman -S base-devel
>
> y
>
> sudo pacman -S git
>
> y
> 
> git clone https://github.com/morrownr/8814au
>
> cd 8814au
>
> git pull
> 
> make
>
> sudo make install
