# Build driver 8814au, 8812au, 88x2bu for rAudio

### 1
```
sudo pacman -Syu
```
>
:: Proceed with installation? [Y/n]
> **n**

### 2
```
sudo pacman -S linux-rpi-headers
```
>
:: Proceed with installation? [Y/n]
> y
>
### 3
>
```
sudo mv -f /usr/lib/modules/6.1.64-2-rpi-ARCH/build /usr/lib/modules/6.1.58-2-rpi-ARCH/
```
>
### 4
> 
```
sudo pacman -S base-devel
```
>
> y
>
### 5
```
sudo pacman -S git
```
>
> y
> 
### 6
>
```
git clone https://github.com/morrownr/8814au
```
### 7
```
cd 8814au
```
>
### 8
>
```
git pull
```
> 
### 9
```
make
```
>
### 10
>

>

```
sudo make install
```
>
### 11
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


