# packages-to-install-for-jetson-tx1
List of packages with sudo apt-get codes for 64 bit Ubuntu 16.04

##Intro
After buying the Jetson TX1, i had searched a lot of tutorials.  But no one has a list of packages that you can install on Jetson successfully.  Hence, i propose a list that contains the sudo apt-get commands to let other users also install all the packages that can reduce the back & forth of searching about the packages.

### How To Contribute

Please read [CONTRIBUTING](/CONTRIBUTING.md).

### How to Share
+ [Share on Twitter](http://twitter.com/home?status=https://github.com/akarsh/packages-to-install-for-jetson-tx1)
+ [Share on Facebook](http://www.facebook.com/sharer/sharer.php?s=100&p[url]=https://github.com/akarsh/packages-to-install-for-jetson-tx1)
+ [Share on Google Plus](https://plus.google.com/share?url=https://github.com/akarsh/packages-to-install-for-jetson-tx1)
+ [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/akarsh/packages-to-install-for-jetson-tx1)

### Index
* [Git](#Git)
* [Code::blocks](#codeblocks)
* [dillo](#dillo)
* [synaptic](#synaptic)
* [midori](#midori)
* [flux](#flux)

###Git
sudo apt-get install git

###code::blocks
sudo apt-get install codeblocks

###dillo
sudo apt-get install dillo

###synaptic
sudo apt-get install synaptic

###midori
sudo apt-add-repository ppa:midori/ppa && sudo apt-get update -qq && sudo apt-get install midori

###flux
sudo add-apt-repository ppa:nathan-renniewaldock/flux && sudo apt-get update && sudo apt-get install fluxgui
