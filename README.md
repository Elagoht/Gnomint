# Gnomint - Linux Mint Gnome

This is actually a Linux distro that based on Linux Mint. I made some changes on it. It has Gnome Shell instead Cinnamon, XFCE or MATE. I love Cinnamon. It's a perfect desktop for new-comers. But I really want to use **auto-tiling** feature on Cinnamon. But we don't have it. So I installed Gnome Shell and Pop OS's shell extension as well. 

I deleted some of unnecessary programs I think they are. The list of deleted apps looks like this:

1. xreader (installed okular instead)
2. hexchat (not necessary)
3. transmission (installed deluge instead)
4. libre-office (installed Softmaker FreeOffice 2021 instead)
5. pix (installed Eye of Gnome instead)
6. thunderbird (installed Geary instead)
7. celluloid (installed Vlc instead)
8. drawing (installed Gimp instead)
9. hypnotix (not necessary)
10. rhythmbox (installed Lollypop instead)
11. xviewer (installed Eye of Gnome instead)
12. mintwellcome (not necessary, because of using Gnome Shell)

Also I added some of repositories I need:

1. ppa:gnumdk/lollypop
2. ppa:mscore-ubuntu/mscore3-stable
3. ppa:apandada1/blanket
4. ppa:lutris-team/lutris
5. https://shop.softmaker.com/repo/linux-repo-public.key

After that, I installed some of software I think they are required:

1. guake
2. gimp
3. python3-pip
4. cheese
5. -y
6. git
7. dialog
8. unzip
9. xmlstarlet
10. gnome-contacts
11. jstest-gtk
12. grub-customizer
13. lollypop
14. kdeconnect
15. geary
16. pavucontrol
17. vlc
18. papirus-icon-theme
19. okular
20. stacer
21. xournal
22. papirus-folders
23. softmaker-freeoffice-2021
24. xclip
25. python3-xlib
26. simplescreenrecorder
27. openjdk-8-jre
28. openjdk-16-jre
29. eog
30. deluge
31. vim
32. gnome-tweaks (I said I install gnome-shell before.)

I also installed my own program **[Passenger](https://github.com/Elagoht/Passenger)**.

I deleted all of Mint themes and installed Fluent and Fluent-dark themes instead.

I set **Fleunt-dark and Papirus-Dark** as system default with dconf.

I removed all of Mint and Ubuntu wallpapers and replace them with *my own drawn* **wallpapers**. I set their configs.

I set lots of **shortcuts** to make usage easier.

I installed HACK font which is required for synth-shell. After that I installed **synth-shell** to customize bash. Now standard user will see a green themed prompt and root user will see a red themed promt and the user will be warned every time entering root user.

I installed some of gnome extensions to make it beautiful and easy to use. Extensions I installed is:

1. appindicatorsupport@rgcjonas.gmail.com
2. fq@megh
3. gnome-fuzzy-app-search@gnome-shell-extensions.Czarlie.gitlab.com
4. gnome-shell-duckduckgo-search-provider@keithcirkel.co.uk
5. lockkeys@vaina.lt
6. noannoyance@daase.net
7. openweather-extension@jenslody.de
8. pop-shell@system76.com
10. screenshot-window-sizer@gnome-shell-extensions.gcampax.github.com
11. sound-output-device-chooser@kgshank.net
12. status-area-horizontal-spacing@mathematical.coffee.gmail.com
13. user-theme@gnome-shell-extensions.gcampax.github.com
14. volume-mixer@evermiss.ne
15. add-to-desktop@tommimon.github.com

**NOTE:** I installed all of these extensions under /etc/skel direction. It means all extension will install as manual install. But everytime a new user will added on system, these extensions will appear on user's shell.

I use **Nemo and Nemo Desktop with Gnome Shell**. Nemo is the best file manager and the best desktop *extension* for Gnome Shell. I added nemo-desktop on startup applications. I also added guake to startup.

Known issues about Pop Shell and Nemo Desktop will cause a graphical bug when using stacked windows with pop shell (Super+S mode).

I added my [VideoSizeRecuder](https://github.com/Elagoht/VideoSizeReducer) and [ImageManipulacitons](https://github.com/Elagoht/ImageManipulactions) nemo actions to make something easier.

# Here Is The Disk Image file

[Mega.io](https://mega.nz/file/6rBmmTLT#KJq5KiTUzMIJfRA3-UTkykmRzhrY5oOKJcjvLAZUn0A)
