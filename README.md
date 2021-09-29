This is a collection of NetHunter Boot-Animations in the Samsung QMG format.
----------------------------------------------------------------------------------

Thanks to Samsung wanting to be special little boys, the good ol bootanimation.zip's do not work, they use qmg format.
This is a proprietary file format for Samsung (as far as I know). 
Back in 2014 we had Samsung Theme Designer which would allow us to create qmg idle-background animations, these qmg files also work for other things.

However Samsung is a bunch of whiny special boys and killed off the project. 

Now you have to use their web-designer but you cannot do that unless you get approved by Samsung as a theme-dev.... Or you are an enterprise customer, who for some reason have a simple as shit to use program for it.



So yeah, I googled for days, couldnt find anything so here I am, making a Github repo for it myself. 









The original files and Images were pulled from the Nethunter Bootanimations tabs.
Sadly I cannot batch create these. 




How I'm doing it:

Create bootanimation ZIP in Nethunter App -> Copy to PC -> Shove it through Samsung Theme Designer 2.0.4 -> Export and rename each Animation individually 
-> Copy back to Phone -> Copy to /system/media -> Set permissions to rw-r--r-- -> Reboot and hope it works lol




To-Do:
- Convert the rest of the Standard Animations
- Redo everything for some different resolutions -> And fix known issue below.
- Make flashable ZIPs for them, or at least a template. (TWRP Flashable, I know it works, should be easy)
- Find out if I can include stock animation in the repo for backup/safety purposes. 


Known Issue(s):

- The resolution of the animations provided are all Full HD, 1920x1080, I cannot really change this other than through cropping. May be able to fix this for my own boot animation but definitely not for everyone.
     > This does not affect the animations other than the shutdown one and then ONLY animations with a non-black background -> It has 2 "empty" or black bars at the top and bottom because my screen is obviously bigger than FullHD. Boot and Botloop display just fine.

----------------------------------------------------------------------------------------------------------------------------------


Happy Hacking! 
			and fuck you Samsung!






