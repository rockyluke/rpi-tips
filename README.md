# rpi-tips

1. [Disclaimer](#disclaimer)
1. [POE](#poe)
1. [Miscellaneous](#miscellaneous)

## Disclaimer

Please read carefully the manual before using any commands on Raspberry PI & Linux..

https://www.raspberrypi.com/documentation/

```bash
man man
```

## POE

### Fan

Edit `/boot/config.txt` & reboot

40000 means 40°C
50000 means 50°C
65000 means 65°C
etc.

```
# POE Fan Speeds
dtparam=poe_fan_temp0=40000
dtparam=poe_fan_temp1=50000
dtparam=poe_fan_temp2=65000
dtparam=poe_fan_temp3=80000
```

## Miscellaneous

```
    ╚⊙ ⊙╝
  ╚═(███)═╝
 ╚═(███)═╝
╚═(███)═╝
 ╚═(███)═╝
  ╚═(███)═╝
   ╚═(███)═╝
```
