Weather Station
=======

Taking this from [http://trastle.github.io/rpi-weather/gettingInstalled.html|Rpi-weather]

## Dependencies


```bash
sudo apt-get install libusb-1.0.0 python-usb python-crypto python-paramiko gnuplot gettext sphinx-common
```

## Install

```bash
mkdir ~/weather
cd ~/weather
git clone https://github.com/jim-easterbrook/pywws.git
cd ~/weather/pywws
make
python setup.py build
sudo python setup.py install
```
