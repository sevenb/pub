<h1>PUB for MAC</h1>

<a href="https://asciinema.org/a/112055" target="_blank"><img src="https://asciinema.org/a/112055.png" /></a>
# **Mobile assets factory command-line program **

PUB is a command-line program to create iOS and Android app icons assets.

Just run pub on the folder with the default icon image(.png 1536x1536) to create all app icons.

Ex: 
~myfolder: pub ios

Run on terminal:

~ pub
  
  or
  
~ pub ios
  
  or
  
~ pub android


### Dependencies ###

**It requires the curl, imagemagick and jquery installed.** 
# Install #

To install it right away for MAC users, copy and paste on terminal:


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
