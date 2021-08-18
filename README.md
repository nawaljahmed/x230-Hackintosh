# x230 Hackintosh Guide

### DON'TSUEMEDON'TSUEMEDON'TSUEMEDON'TSUEMEDON'TSUEMEDON'TSUEME

**Update: I have swtiched to a Thinkpad T440p with macOS Mojave on it. The x230i is now by backup laptop. I wrote a guide for the T440p [here](https://github.com/NawalJAhmed/T440p-Hackintosh). The T440p guide is FAR more extensive in Hackintoshing than this one, so it's a good idea to look at it anyway even if you don't have one.**

A guide for anyone trying to Hackintosh their Thinkpad x230. I actually used a x230i and it worked the exact same.

<p align="center">
  <img src="https://user-images.githubusercontent.com/11577850/64479428-0c603d00-d185-11e9-8c3e-6c30f41f5ffe.png">
  <br>
  <em> macOS Mojave on a x230i </em>
</p>

You will need a Mac Disk Image File of the OS you want. When I tried this, I used an image of Mojave 10.14.3 with Clover. A simple way to obtain this is by using an actual Mac that you borrow from a friend or get from a library and downloading from the App store. If you cannot find the file you want, do not worry. Apple has a bad habit of removing the quick find of previous operating systems on their App Store. The previous ones are hidden and are only found in this archive. Go here are select the OS you want. Then scroll down to downloads. For very old versions, they might provide a .dmg file. Remember that you need a .dmg file.

- You can use Clover for the bootloader which makes this very easy. [Here you can learn more about Clover](https://wiki.archlinux.org/index.php/Clover).
- [Transmac](https://www.acutesystems.com/scrtm.htm) will load the disk image file onto a USB drive. It is paid-for but they provide a 14 day trial so that is plenty of time.

Also remember that in the BIOS, change the boot option to UEFI instead of Legacy, and to switch the fn key and ctrl key since Thinkpad laptops and regular key placements are different.

[This video tutorial by Jack Zhang](https://www.youtube.com/watch?v=ajdAlnwZhkk) is very helpful in how to install macOS on the x230. It is mostly in Chinese but it is easy enough to follow. His channel might even have some more updated videos for newer macOS versions.

When you succed in Hackintoshing your laptop, you will want to change your special keys to something you are more used to. Aside from the regular macOS keyboard settings, you can use Karabiner Elements to fully swap the actions of your keys to whatever you want.

## EFI Files

- [X230 Hackintosh Files](http://www.mediafire.com/file/59zlwzmy2u1ag8r/X230_Mojave_Hackintosh_Files.7z/file) - This is required.
- [Mojave 10.14.3 EFI](http://www.mediafire.com/file/m6zx6wzjsu62ydj/X230_Mojave_10.14.3_EFI.7z/file)
- [Mojave 10.14.5 EFI](http://www.mediafire.com/file/ycg3f3sit02hrvy/X230_Mojave_10.14.5_EFI.7z/file)

### x320 Hackintosh Files

<p align="center">
  <img src="https://user-images.githubusercontent.com/11577850/64479495-fd2dbf00-d185-11e9-9354-cdb15159746f.png">
  <br>
  <em> x320 Hackintosh Files </em>
</p>

### Clover Mount EFI

<p align="center">
  <img src="https://user-images.githubusercontent.com/11577850/64479497-0323a000-d186-11e9-9101-d5eec79dad98.png">
  <br>
  <em> Clover Mount EFI </em>
</p>

### EFI Files

<p align="center">
  <img src="https://user-images.githubusercontent.com/11577850/64479500-07e85400-d186-11e9-8c86-b73890e93680.png">
  <br>
  <em> EFI Files </em>
</p>

---

Please keep in mind, that I had this Hackintosh for about a week. At the end of the week, I reflected and realized the if I was going to use macOS, I might as well use another UNIX based OS. I switched back to Linux. It was fun while it lasted, but at this point I can safely say a Linux/Windows dual boot is my way to go. For Linux, I prefer either Debian or Arch. I like using KDE Plasma as my desktop environment and window manager. However, a tiling window manager like i3, xmonad, or openbox is really good for efficiency if you can get the keyboard commands down. For now, I'm good with KWin. Maybe I'll even go back to a Hackintosh again just to get used to the workflow.
