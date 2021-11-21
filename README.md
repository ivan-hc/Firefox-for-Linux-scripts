# Firefox-for-Linux-scripts
Easily install and remove official Firefox Stable, Beta, DevEdition, Nightly and ESR versions on GNU / Linux using my scripts.

Each of these scripts is inspired by [the official Debian/Firefox wiki page](https://wiki.debian.org/Firefox#From_Mozilla_binaries), and will add:
- a folder in / opt containing the official version of Firefox you want, plus a script I made to remove all the files that will be installed;
- a launcher in / usr / share / applications;
- a symbolic link in / usr / local / bin.

# Firefox Stable
### Install
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox && chmod a+x ./firefox && sudo ./firefox`
### Uninstall
`sudo /opt/firefox/remove`

------------------------------------
# Firefox ESR
### Install
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-esr && chmod a+x ./firefox-esr && sudo ./firefox-esr`
### Uninstall
`sudo /opt/firefox-esr/remove`

------------------------------------
# Firefox Beta
### Install
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-beta && chmod a+x ./firefox-beta && sudo ./firefox-beta`
### Uninstall
`sudo /opt/firefox-beta/remove`

------------------------------------
# Firefox DevEdition
### Install
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-dev && chmod a+x ./firefox-dev && sudo ./firefox-dev`
### Uninstall
`sudo /opt/firefox-dev/remove`

------------------------------------
# Firefox Nightly
### Install
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-nightly && chmod a+x ./firefox-nightly && sudo ./firefox-nightly`
### Uninstall
`sudo /opt/firefox-nightly/remove`
