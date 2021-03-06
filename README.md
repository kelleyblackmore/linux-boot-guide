# linux-boot-guide


### Choose a boot option

Step one: Download a Linux OS. 

Step two: Create a bootable CD/DVD or USB flash drive.

Step three: Boot that media on the destination system

download Linux from Mint or Ubuntu or whatever site hosts the version you want. That download will likely consist of a single ISO file. Note: An older computer may have a 32-bit processor, which won't work with 64-bit versions of Linux.

The second part -- creating boot media -- requires a little thought. The fastest, easiest method is to use a flash drive, even if the destination system has a CD/DVD drive. Indeed, the only reason not to go the flash-drive route is if the destination system won't boot from one. 

My advice: Try a flash drive first. If it doesn't work, you can always use that same ISO file to create a bootable CD later.


Build your boot drive


Once you've downloaded your Linux ISO, you'll need a utility that can create a bootable flash drive. 
Rufus free and easy to use. Download the portable version; there's no need to actually install it, because most likely you'll just run it once.

Step 1: Plug in your flash drive then run the Rufus utility.

Step 2: In the Device field, at the very top, make sure your flash drive is the one selected. If not, click the pull-down and select it.

Step 3: Near the checkbox marked "Create a bootable disk using," click the little disk icon and navigate to the Linux ISO file you downloaded. It's most likely in your Downloads folder. Click it, then click Open.

Step 4: If you like, you can change the "New volume label" field to something like "Linux," but it's not necessary. Click Start, then wait while the drive is formatted and the ISO installed.

Get ready to boot
Now it's time to turn your attention to the destination system. It doesn't matter what condition it's in or even if it's riddled with malware; you just need it to be able to boot from a flash drive.

That may mean venturing into the BIOS and changing the boot order, which by default almost certainly puts the hard drive first. Some systems do offer a pop-up boot menu that lets you choose what device to boot from without having to monkey with the settings. If yours does, count yourself lucky.

hit F10 or may be F1

Once you've found your way into the BIOS, find the boot or startup menu and make sure "flash drive" or "USB drive" is first in the boot order. 

Then save and exit.



Linux can boot and run right from the flash drive -- no actual installation required.

The big decision you'll need to make is whether you want to install Linux alongside your existing OS, which would result in a dual-boot setup, or reformat the hard drive and run only Linux. The former is worth considering if the system has a large drive and can easily accommodate both operating systems, or you still have need for Windows.

This following instructions may vary a bit from one distro to the next, but they're based on my installation of Linux Mint.

Step one: Boot from the flash drive directly into Linux.

Step two: Double-click the Install Linux icon on the desktop.

Step three: Make any requested selections regarding language, installation of third-party software and so on. Then choose your OS installation preference: alongside the existing OS or erase-and-install.


