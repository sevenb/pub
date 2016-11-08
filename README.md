# **pub command-line program for UNIX **
MOBILE ASSETS FACTORY

PUB is a command-line program to create iOS and Android app icons assets.

Just run pub on the folder with the default icon image(.png 1536x1536) to create all app icons.

Ex: 
~myfolder: pub ios

To create only for one platform, use ios or android parameters.

~ pub

~ pub ios

~ pub android

### Dependencies ###

**It requires the curl, imagemagick and jquery installed.** but pub will try to install automatically all dependencies needed.

# Install #

To install it right away for all UNIX users (Linux, OS X, etc.), copy and paste on terminal:


```
#!shell

sudo wget https://raw.githubusercontent.com/sevenb/pub/master/pub -O /usr/local/bin/pub
sudo chmod a+rx /usr/local/bin/pub
```

or 


```
#!shell

sudo curl -L https://raw.githubusercontent.com/sevenb/pub/master/pub -o /usr/local/bin/pub
sudo chmod a+rx /usr/local/bin/pub
```
