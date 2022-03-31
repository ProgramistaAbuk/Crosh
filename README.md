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

