# A Raspberry Pi, Capybara Powered Spotify Alarm Clock
-------------
## Overview
#### Wake up to your favorite music on your favorite speakers.
###### NOTE: This tutorial assumes a Spotify Premium Account
-----------------------------------------------
This will guide you through the way I set up my Raspberry Pi to become a Spotify
Alarm Clock using Capybara.

## Setup
### 1. Buy a Raspberry Pi
This is my first Raspberry Pi project! Woo!

### 2. Install Pi Dependencies
In order to get a workable user interface, we have to set a few things up.
I followed this great tutorial to set up
the basics, and then I followed this tutorial to set up my Pi so that I could
keep it in my drawer and work on the Pi from my Laptop.

### 3. Install Capybara Dependencies
This Spotify awakening script is driven off of Capybara, a browser scripting
tool originally made for testing but usable for all sorts of cool stuff.

#### INSTALL RUBY
Capybara is a Ruby Gem, so we need Ruby:
`sudo apt-get install Ruby`

#### INSTALL RBENV
But, as ??? mentions, we need at least verion 1.9.3 of Ruby, so let's get rbenv
- a terrific Ruby versioning system.
`RBENV

#### INSTALL PhantomJS
Let's download the PhantomJS binary, extract the tarball and copy bin/phantomjs
into our path. We'll then source our bashrc file for that change to take
affect:

```bash
wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.8-linux-x86_64.tar.bz2 ~/.rbenv/bin
echo 'source $PATH:$HOME/.rbenv/bin' >> ~/.bashrc
source ~/.bashrc
```


