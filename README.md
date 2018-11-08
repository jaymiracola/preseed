# Preseed - No Stop
Making Ubuntu 18.04 strictly look to preseed file for boot via PXE.
##Dnsmasq
After installing dnsmasq, use the included config file to enable tftp, dhcp, etc. The location for tftp is also identified in the config.
##Grub
Place the grub config as /srv/tftp/grub/grub.cfg
[Debian Preseed](https://www.debian.org/releases/wheezy/ia64/apbs02.html.en) The most useful resource when identifying kernel boot paramters.
##Preseed Config
Place the included preseed file /srv/tftp/.
