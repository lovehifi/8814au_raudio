# Build driver rtl8814au, rtl8812au, rtl8812bu/rtl8822bu, rtl8832bu/rtl8852bu, rtl8821au, rtl8821cu for rAudio

### #1
```
sudo pacman -Syu
```
>
:: Proceed with installation? [Y/n]
> **n**

### #2
```
sudo pacman -S linux-rpi-headers
```
>
:: Proceed with installation? [Y/n]
> y
>
### #3
>
```
sudo mv -f /usr/lib/modules/6.1.64-2-rpi-ARCH/build /usr/lib/modules/6.1.58-2-rpi-ARCH/
```
>
### #4
> 
```
sudo pacman -S base-devel
```
>
> y
>
### #5
```
sudo pacman -S bc
```
>
> y
>
>
### #6
```
sudo pacman -S git
```
>
> y
> 
### #7
>
```
git clone https://github.com/morrownr/8814au
```
### #8
```
cd 8814au
```
>
### #9
>
```
git pull
```
> 
### #10
```
make
```
>
### #11
>
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
&nbsp;
>
For rtl8812bu/rtl8822bu
>
> git clone https://github.com/morrownr/88x2bu-20210702.git
>
&nbsp;
>
For rtl8821au
>
> git clone https://github.com/morrownr/8821au-20210708.git
>
&nbsp;
>
For rtl8821cu
>
> git clone https://github.com/morrownr/8821cu-20210916.git
>
&nbsp;
>
For rtl8832BU and rtl8852BU
>
> git clone https://github.com/morrownr/rtl8852bu.git
>
&nbsp;
>

