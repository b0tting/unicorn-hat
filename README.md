![Unicorn HAT/pHAT](unicorn-hat-logo.png)

Available from Pimoroni:  
http://shop.pimoroni.com/products/unicorn-hat  
http://shop.pimoroni.com/products/unicorn-phat

###`unicornhat` Python Library & Examples

Here you'll find everything you need to start lighting up your Unicorn HAT or pHAT using python.

Python users should probably ignore most of this repository and just:

**Full install for beginners:**

```bash
\curl -sS get.pimoroni.com/unicornhat | bash
```

**Install for Python 3 ( idle3 ):**

```bash
sudo apt-get install python3-pip python3-dev
sudo pip-3.2 install unicornhat
```

**Install for Python 2 ( idle ):**

```bash
sudo apt-get install python-pip python-dev
sudo pip install unicornhat
```

**Install from Github clone**

```
git clone https://github.com/pimoroni/unicorn-hat
cd unicorn-hat/
sudo apt-get install python-dev
cd library/rpi-ws281x
sudo python setup.py install
cd ../..
cd library/UnicornHat
sudo python setup.py install
cd ../..
```

Then proceed to [examples](examples).

###Using with idle/idle3:

`unicornhat` needs root access to function. Please make sure you start LXTerminal and run idle or idle3 with the "sudo" command like so:

```bash
sudo idle
```

###Based Upon rpi_ws281x

`unicornhat` is based upon a modified, Pi 2/3 compatible version of the RPi ws281x Library by Jeremy Garff.

The library was modified by Richard Hirst.

* Modified version: https://github.com/richardghirst/rpi_ws281x
* Original: https://github.com/jgarff/rpi_ws281x

###RaspberryPi-NeoPixel-WS2812

Note: `unicornhat` is no longer based upon this library, but this information is included for posterity.

`unicornhat` was previously based upon a modified version of the ws2812 C driver from: https://github.com/626Pilot/RaspberryPi-NeoPixel-WS2812
