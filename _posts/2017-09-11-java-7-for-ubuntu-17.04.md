---
Title: "java 7 for ubuntu 17.04"
date: 2017-09-11 12:58:00 -0600
categories: system
permalink: java7
---
Install Java 7 to ubuntu 17.04 or any other ubuntu that doesn't support version 7.
------------------------------------------------------------------------

Long story short: I need to install java version 7 to ubuntu 17.04, newer version of ubuntu won't support older versions than 8.

I tried create a deb package with the make-jpkg from the java-package package but it failed.
I also tried to install openjdk-7 from debs of older version of ubuntu, also failed...

So I followed [this guide](https://www.digitalocean.com/community/tutorials/how-to-manually-install-oracle-java-on-a-debian-or-ubuntu-vps) with the oracle package for version 7 from [here](http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase7-521261.html).

Update the alternative with:

    sudo update-alternatives --config java

So far so good.
