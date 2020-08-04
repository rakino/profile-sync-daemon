Since the author does not want to add official support for every browser clone [#208](https://github.com/graysky2/profile-sync-daemon/issues/208#issuecomment-323164345), I forked the repository and might add more config files :)

# Profile-sync-daemon
Profile-sync-daemon (psd) is a tiny pseudo-daemon designed to manage your browser's profile in tmpfs and to periodically sync it back to your physical disc (HDD/SSD). This is accomplished via a symlinking step and an innovative use of rsync to maintain back-up and synchronization between the two. One of the major design goals of psd is a completely transparent user experience.

## Good Advice
Always backup your browser profile(s) before using psd for the first time.

## Users of eCryptFS
User of eCryptFS are encouraged not to use psd unless willing to help troubleshoot suspected browser corruption. See [#158](https://github.com/graysky2/profile-sync-daemon/issues/158).

## Supported Browsers
* Chromium
* Conkeror
* Epiphany
* Firefox (stable, beta, and aurora)
* Firefox-trunk (this is an Ubuntu-only browser: http://www.webupd8.org/2011/05/install-firefox-nightly-from-ubuntu-ppa.html)
* Google Chrome (stable, beta, and dev)
* Heftig's version of Aurora (this is an Arch Linux-only browser: https://bbs.archlinux.org/viewtopic.php?id=117157)
* Icecat (GNU version of Firefox)
* Iceweasel (Debian version of Firefox)
* Inox (https://bbs.archlinux.org/viewtopic.php?id=198763)
* LibreWolf (A fork of Firefox, focused on privacy, security and freedom.)
* Luakit
* Midori
* Opera, Opera-Beta, Opera-Developer, and Opera-Legacy
* Otter-browser
* Palemoon
* QupZilla
* Qutebrowser
* Rekonq
* Seamonkey
* Surf (http://surf.suckless.org/)
* Vivaldi-browser and Vivaldi-browser-snapshot
* Waterfox Current (Optimized fork of Firefox ESR)

## Documentation
Consult the man page or the wiki page: https://wiki.archlinux.org/index.php/Profile-sync-daemon

## Installation from Source
To build from source, see the included INSTALL text document.
