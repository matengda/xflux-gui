f.lux indicator applet
======================
Better lighting for your computer

f.lux indicator applet is an indicator applet to control xflux, an application
that makes the color of your computer's display adapt to the time of day, warm
at nights and like sunlight during the day

Install Instructions
--------------------

### Ubuntu/Debian

```bash
# Install dependencies
sudo apt-get install git python-appindicator python-xdg python-pexpect python-gconf python-gtk2 python-glade2 -y

# Download and install xflux-gui
cd /tmp
git clone "https://github.com/xflux-gui/xflux-gui.git"
cd xflux-gui
sudo python ./setup.py install

# Run flux
fluxgui
```

License
-------

The f.lux indicator applet is released under the **MIT License**.
