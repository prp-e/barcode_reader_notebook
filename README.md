# Barcode reader notebook

A very simple barcode experiment I've done in python. I guess it can be better than most of the projects you find on the internet. 

## Libraries 

* `pyzbar` 
* `python-barcode`
* `matplotlib-pyplot`

## `pyzbar` installation 

### On OS X 

On OS X (they call it macOS now, but I love the name OS X, it was badass), you have to install _zbar shared library_ by this command:

```
brew install zbar
```

remember this thing can download a __huge__ amount of packages, so if you're out of disk space it's better to not install that :)) 

### On Linux

The shared library on Linux (I use Ubuntu/Debian, and not other distros. PR's are always appreciated for guides) you install the shared library by this command:

```
sudo apt install libzbar0
```

apparently, this command installs the python libraries as well. 

### Windows 

I don't run my codes on Windows, so if you want to run this code on windows, please take a look at [project page](https://pypi.org/project/pyzbar/) on python's network. By the way, you always can make me happy by sending a PR. 
