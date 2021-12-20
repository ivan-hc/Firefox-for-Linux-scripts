Easily install and remove official Firefox releases (Stable, Beta, DevEdition, Nightly and ESR) on any GNU/Linux distribution (32 and 64 bit) using my scripts.
Each of these scripts is inspired by [the official Debian/Firefox wiki page](https://wiki.debian.org/Firefox#From_Mozilla_binaries), and will add a folder in /opt (containing the official version of Firefox you want, plus a script I made to remove all the files that will be installed), a launcher in /usr/share/applications and a symbolic link in /usr/local/bin.

Use the following links to navigate on this page:

- [Firefox Stable](#firefox-stable)
- [Firefox ESR](#firefox-esr)
- [Firefox Beta](#firefox-beta)
- [Firefox DevEdition](#firefox-devedition)
- [Firefox Nightly](#firefox-nightly)

Learn more about ["AM", the Application Manager for GNU/Linux](https://github.com/ivan-hc/AM-application-manager) that only installs/removes/updates/manages/allows standalone programs.

------------------------------------
# Firefox Stable
### Install (64 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox && chmod a+x ./firefox && sudo ./firefox`
### Install (32 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-32 && chmod a+x ./firefox-32 && sudo ./firefox-32`
### Uninstall (64/32 bit)
`sudo /opt/firefox/remove`

------------------------------------
# Firefox ESR
### Install (64 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-esr && chmod a+x ./firefox-esr && sudo ./firefox-esr`
### Install (32 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-esr-32 && chmod a+x ./firefox-esr-32 && sudo ./firefox-esr-32`
### Uninstall (64/32 bit)
`sudo /opt/firefox-esr/remove`

------------------------------------
# Firefox Beta
### Install (64 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-beta && chmod a+x ./firefox-beta && sudo ./firefox-beta`
### Install (32 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-beta-32 && chmod a+x ./firefox-beta-32 && sudo ./firefox-beta-32`
### Uninstall (64/32 bit)
`sudo /opt/firefox-beta/remove`

------------------------------------
# Firefox DevEdition
### Install (64 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-dev && chmod a+x ./firefox-dev && sudo ./firefox-dev`
### Install (32 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-dev-32 && chmod a+x ./firefox-dev-32 && sudo ./firefox-dev-32`
### Uninstall (64/32 bit)
`sudo /opt/firefox-dev/remove`

------------------------------------
# Firefox Nightly
### Install (64 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-nightly && chmod a+x ./firefox-nightly && sudo ./firefox-nightly`
### Install (32 bit)
`wget https://raw.githubusercontent.com/ivan-hc/Firefox-for-Linux-scripts/main/firefox-nightly-32 && chmod a+x ./firefox-nightly-32 && sudo ./firefox-nightly-32`
### Uninstall (64/32 bit)
`sudo /opt/firefox-nightly/remove`

------------------------------------
# These and more scripts will be available on my new repository, at [ivan-hc/AM-application-manager](https://github.com/ivan-hc/AM-application-manager).
