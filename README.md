# **pub command-line program for UNIX **
MOBILE ASSETS FACTORY

PUB is a command-line program to create iOS and Android app icons assets.

Just run pub on terminal to create all app icons.

To create only for one platform, use the parameter ios or android.


**It requires the curl, imagemagick and jquery installed.** but pub will try to install automatically all dependencies needed.

~ pub
~ pub ios
~ pub android

### Dependencies ###

* Python 
* Wget

# Install #

To install it right away for all UNIX users (Linux, OS X, etc.), copy and paste on terminal:


```
#!shell

sudo wget https://github.com/sevenb/pub/blob/master/pub -O /usr/local/bin/pub
sudo chmod a+rx /usr/local/bin/pub
```

or 


```
#!shell

sudo curl -L https://github.com/sevenb/pub/blob/master/pub -o /usr/local/bin/pub
sudo chmod a+rx /usr/local/bin/pub
```
