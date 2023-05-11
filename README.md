# Open-RGB-Microphone-Access-Mac-OS
Enable Microphone Access for open RGB in Mac OS

Issue with Audio Sync via Mac

This process would work fine on windows, as windows would ask permissions for Microphone but on a mac, it wasn’t allowed to access the microphone.

When I tried to enable it from the settings, it didn’t show any options for giving the microphone permissions. There was no solution for this online. 
 
I had ran into this issue with the similar issue with another app keyboard visualizer, so I had to run the file in terminal to access the microphone which was an issue addressed on Github. So, I did the same thing here and surprisingly it worked. So, since this was a huge issue for Mac users, I uploaded the work around for Mac users on Github.

To make Open RGB access the microphone on a Mac, 
 * Open finder and search for Open RGB
 
 * Right Click on the Open RGB icon and select SHOW PACKAGE CONTENTS


 
	Select Contents > Mac OS > Open RGB

	Run this file in terminal

	It should open Open RGB and ask for microphone permissions.

 
Unfortunately, every time you need to repeat this process every time and leave the terminal running while you use Open RGB
