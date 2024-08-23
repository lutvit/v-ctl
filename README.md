v-ctl
==================================================

v-ctl is a web hosting control panel for virtual and bare-metal servers that was originally forked from VestaCP. The focus is on stability, lightweight, flexibility and new features. The long-term goal is to create an entirely independent web hosting panel with all the features that make it convenient and easy to manage the complete web hosting environment while being as stable and flexible as possible.

* v-ctl is an open source hosting control panel that was originally forked from VestaCP.
* It is not intended as a replacement for the VestaCP or its forks.
* It was developed and optimized for the current Debian operating system and is NOT compatible with Ubuntu.
* The focus is on the further development and modernization of the entire system, without paying attention to compatibility with VestaCP or its forks.
* The web interface has a clean and focused interface without the clutter.
* Feature requests and user reports on issues are always welcome and will be integrated into the core as quickly as possible.

How to install (2 step)
----------------------------
Connect to your server as root via SSH
```bash
ssh root@your.server
```

Download the installation script, and run it:
```bash
curl https://vestacp.com/pub/vst-install.sh | bash
```

How to install (3 step)
----------------------------
If the above example does not work, try this 3 step method:
Connect to your server as root via SSH
```bash
ssh root@your.server
```

Download the installation script:
```bash
curl -O https://vestacp.com/pub/vst-install.sh
```
Then run it:
```bash
bash vst-install.sh
```
Exclusion of liability
----------------------------
The use of v-ctl is at your own risk. The author accepts no liability for damages that may arise or have arisen through the use of this software. The author is also not liable for damage caused by faulty updates of the software.

License
----------------------------
Vesta is licensed under  [GPL v3 ](https://github.com/outroll/vesta/blob/master/LICENSE) license

