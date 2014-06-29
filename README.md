aaa-admin-scripts
=================

admin scripts

aaa-add-ppa
usage: ubunturelease ppa:user/ppa-name

aaa-aliases
depreciated---- aliases added manually in .bash_aliases and symlinked from gitdir to home dir via aaa-linkup

aaa-android-alternatives
sets up alternatives for fastboot and adb between the sdk versions and debian versions
----needs work since renaming /usr/bin/adb will fuck up debian packaging system

aaa-edit-ramdisk
script to edit selected files within android kernel image ramdisk
this includes decompressing the disc and recompressing afterwards

aaa-kali-pkg-check
script checks each package on system to see if it should be a kali package but is not
-----working but needs little tidying and error checking

aaa-linkup
symlinks various files from the github dir to various system locations
allows a central location to update/keep working on files

aaa-meminfo
coppied script which displays advanced mem use info


aaa-mod-deps
script to modify deps in dbian package

aaa-wordlists
setup wordlists on kali sysem

STATUS: nearly done
