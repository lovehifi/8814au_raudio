# Build driver 8814au, 8812au, 88x2bu for rAudio


```
sudo pacman -Syu
```
>
:: Proceed with installation? [Y/n]
> **n**

```
sudo pacman -S linux-rpi-headers
```
>
:: Proceed with installation? [Y/n]
> y
>
```
sudo mv -f /usr/lib/modules/6.1.64-2-rpi-ARCH/build /usr/lib/modules/6.1.58-2-rpi-ARCH/
```

> 
```
sudo pacman -S base-devel
```
>
> y
>
```
sudo pacman -S git
```
>
> y
> 
```
git clone https://github.com/morrownr/8814au
```

```
cd 8814au
```
>
```
git pull
```
> 
```
make
```
>
```
sudo make install
```
>

-----------
For rtl8812au
>
> git clone https://github.com/morrownr/8812au-20210629.git
>
For rtl88x2bu
>
> git clone https://github.com/morrownr/88x2bu-20210702.git
>


