## A dark minimalistic theme
A dark style theme for the rEFInd boot manager.

![default](https://github.com/itsrdb/refind-snow/blob/master/screen1.png)
![dark](https://github.com/itsrdb/refind-snow/blob/master/screen2.png)
![red](https://github.com/itsrdb/refind-snow/blob/master/screen3.png)

[rEFInd](http://www.rodsbooks.com/refind/) is an easy to use boot manager for UEFI
based systems. This is a clean and minimal theme for it.

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/refind-snow/theme.conf` at the end of
    `refind.conf`.
    
 ### All new icons and darker backgrounds!
 
 There are three backgrounds included with the theme pitch black, gradient red and a dark themed wallpaper. Each of them can be used instead of the black(default) by renaming it to 'background.png'. You can also use any background of your choice.
 
 ### Special thanks to:
 
 [rEFInd-minimal theme](https://github.com/EvanPurkhiser/rEFInd-minimal)
 [rEFInd-minimal-black](https://github.com/andersfischernielsen/rEFInd-minimal-black)
 Adobe XD Developers.
