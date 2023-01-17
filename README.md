This is a collection of NetHunter Boot-Animations in the Samsung QMG format.
----------------------------------------------------------------------------------------------------------------------------------

Thanks to Samsung wanting to be special little boys, the good ol bootanimation.zip's do not work, they use qmg format.
This is a proprietary file format for Samsung (as far as I know). 
Back in 2014 we had Samsung Theme Designer which would allow us to create qmg idle-background animations, these qmg files also work for other things.

However Samsung is a bunch of whiny special boys and killed off the project and removed all download links. 

Now you have to use their web-designer but you cannot do that unless you get approved by Samsung as a theme-dev.... Or you are an enterprise customer, who for some reason have a simple as shit to use program for it.

So yeah, I googled for days, couldnt find anything so here I am, making a Github repo for it myself. 

The original files and Images were pulled from the Nethunter Bootanimations tabs and other open source sites. (apart from the original files obviously)


Sadly I cannot batch create these but hey, the manual work paid off. :)

----------------------------------------------------------------------------------------------------------------------------------

File Information:

- bootsamsung.qmg - The first bootanimation that plays after the Samsung logo (pretty sure that's too deep down to edit too)

- bootsamsungloop.qmg - This file plays after bootsamsung.qmg and has to be a perfect loop, it will play until the boot is actually finished.

- shutdown.qmg - Plays on shutdown as the name suggests.

----------------------------------------------------------------------------------------------------------------------------------

Content:

     - Nethunter Classic 
     - Nethunter Glitch
     - Nethunter New Kali
     - Nethunter ctOS
     - Nethunter Classic+ctOS combo (ctOS shutdown, looks better than the NH one imo)
     - Easteregg Handcrafted because I was bored
     - Samsung Original Boot Animation

----------------------------------------------------------------------------------------------------------------------------------

How I'm doing it:

Create bootanimation ZIP in Nethunter App 
-> Copy to PC 
-> Shove it through Samsung Theme Designer 2.0.4 
-> Export and rename each Animation individually 
-> Copy back to Phone 
-> Copy to /system/media 
-> Set permissions to rw-r--r-- 
-> Reboot and hope it works lol

----------------------------------------------------------------------------------------------------------------------------------

 User instructions:
 
-> Copy back to Phone 
-> Copy to /system/media 
-> Set permissions to rw-r--r-- 
-> Reboot and hope it works lol
----------------------------------------------------------------------------------------------------------------------------------

To-Do:
- Make flashable ZIPs for them, or at least a template. (TWRP Flashable, I know it works, should be easy)
- More custom animations. 



Done:
- Find out if I can include stock animation in the repo for backup/safety purposes. - Done, dont care if its copyrighted, I'll take it down if I have to.
- Convert the rest of the Standard Animations - All done except that burning one, I dont think anyone over 12 uses one as edgy as that. lols



Most likely can't/won't fix:
- Redo everything for some different resolutions -> Check "Known issues" below.

----------------------------------------------------------------------------------------------------------------------------------

Known Issue(s):

- The resolution of the animations provided are all Full HD, 1920x1080, I cannot really change this other than through cropping. May be able to fix this for my own boot animation but definitely not for everyone.
     > This does not affect the animations other than the shutdown one and then ONLY animations with a non-black background -> It has 2 "empty" or black bars at the top and bottom because my screen is obviously bigger than FullHD. Boot and Bootloop animations display just fine.

----------------------------------------------------------------------------------------------------------------------------------

Happy Hacking and fuck you Samsung!






