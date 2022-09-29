# Crosh
### Wifi Power Save
---------------
```bash
wifi_power_save
```
 Options =  [status | enable | disable]

```bash 
wifi_power_save status
```
 Output = Power save: on
 
 Output 2 = Power save: off
 
 Description: Shows if wifi power save is on or off

```bash 
wifi_power_save enable
```
 Output: Power save: on
 
 Description: Turns on wifi power save [smaller power usage but slower/worse wifi]

```bash 
wifi_power_save disable
```
 Output: Power save: off
 
 Description: Turns off wifi power save [bigger power usage but better/faster wifi]

### Top
---------------
```bash
top
```
Description: Chromebook Equivalent to a [Task Manager]

### Uname
---------------
```bash
uname -a
```
Description: Shows all your system information

### Ping
---------------
```bash
ping -c 2 -i 5 -s 2 -W 4 10.101.248.152
```

Options: ping -c count  -i interval -s package size -W wait time

Output: 10 bytes from 10.101.248.152: icmp_seq=1 ttl=64 [Your's maye look different]

Description: Pings website or ip address of internet

### Evtest
---------------
```bash
evtest
```

Options: 
/dev/input/event0:      Lid Switch
/dev/input/event1:      Power Button
/dev/input/event2:      Video Bus
/dev/input/event3:      AT Translated Set 2 keyboard
/dev/input/event4:      Elan Touchpad
/dev/input/event5:      acpd7219m98357 Headset Jack
/dev/input/event6:      HDA ATI HDMI HDMI/DP,pcm=3
/dev/input/event7:      HDA ATI HDMI HDMI/DP,pcm=7

Output: (Too long to write but mainly the log of the test)

Description: Gves option to test 8 different components on chromebook

### Rollback
---------------
```bash
rollback
```

Options: y/N

Description: Go back one version on chromebook
