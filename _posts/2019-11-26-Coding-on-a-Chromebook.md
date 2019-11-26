---
layout: post
title: Coding on a Chromebook
date: 2019-11-26
---
  Coding on a Chromebook can be just as hard as finding a good place to get started coding. Beyond very limited learning 
websites, online editors, and file sharing services like github, which this website is made on, Chromebooks don't have a lot to 
offer to developers. If you want to create complex systems and edit code the built in text editor just isn't good enough. There 
are a lot of tutorials out there for going into dev mode on your chromebook and dual booting Linux. Some people just don't want
to go through all those steps to get a simple code editor up and running. There are many reasons not to do this including that 
it voids your warranty and requires you to wipe your chromebook. There is a way to get Linux on a chromebook that doesn't void
your warranty or require you to wipe your Chromebook. Google recently added a way to enable Linux apps to run on a Chromebook.
To enable itall you have to do is go to the Settings app and look and either type "Linux(beta)" into the search bar or click on
"Linux beta" from the list of options from the sidebar. Once you find the Linux beta option just click turn on. After you turn 
on Linux beta it will ask you if you want to install the Linux environment just click install this will take a while to install 
so be patient. Once Linux is installed a Linux terminal will appear in your app drawer. Once the Linux terminal appears open it 
and type the following line of code into the command line:
```bash
sudo apt-get update && sudo apt-get upgrade
```
This command gets sudo priviledges to fetch updates and then gets sudo priviledges to update everything. We run this command 
first to make sure everything is up to date. That's it now you have Linux. There is so much you can do with Linux. Since the
Linux version on Chromebooks comes with the apt manager pre installed all you have to do to install most apps is type:
```bash
sudo apt-get install name-of-program
```
replacing `name-of-program` with the name of the program you want to install. For example if you want to install IDLE3 to code
python you would type in:
```bash
sudo apt-get install IDLE3
```
and wait for IDLE3 to install. If you want to install a program that you can't install with the command line all you have to do 
is find the install for the program and install it. After you install it either move the program to the Linux files folder 
under "My Files" or share the folder that the program is in with Linux by two-finger clicking on the folder and clicking "Share 
With Linux". Next two-finger click on the install file and click on "Install with Linux" and wait for it to install. Once the 
program is installed it will appear in your app drawer. Hope this helps anyone trying to code on a Chromebook.
