# Compiling under Ubuntu 22.04

1. `sudo apt install libssl-dev`
2. `git clone https://github.com/mozilla-b2g/valgrind.git`
3. `https://github.com/philippe44/TinySVCmDNS.git tinysvcmdns`
4. `git clone https://github.com/mrjimenez/pupnp-backup.git libupnp`
5. `cd libupnp && git checkout branch-1.6.x`
6. `mv upnp/inc/upnpconfig.h.in upnp/inc/upnpconfig.h`
7. `git clone https://github.com/philippe44/mDNS-SD.git mdnssd`
8. `cd mdnssd && git checkout v2`
9. `wget https://ftp.osuosl.org/pub/xiph/releases/flac/flac-1.3.4.tar.xz`
10. `tar -xf flac-1.3.4.tar.xz`
11. `git clone https://github.com/akheron/jansson.git`
12. `git clone https://github.com/toots/shine.git`
13. `git clone https://github.com/mattstevens/dmap-parser.git`


# Next steps

Copmile libixml from inside libupnp to get libixml.a
