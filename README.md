Phenom-OS OREO
===========
**The Power TO Be Your Best**

Credits
-------
* [**GZOSP (Base)**](https://github.com/AOSP-JF-MM)
* [**JDCTEAM**](https://github.com/AOSP-JF-MM)
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Pure Nexus**](https://github.com/PureNexusProject)

How to Build?
-------------

To initialize your local repository using the Phenom-OS trees, use a 
command like this:

```bash
  repo init -u git://github.com/Phenom-OS/manifest.git -b 8.0
```
  
Then to sync up:
----------------

```bash
  repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch phenom_device_codename-userdebug
  make bacon -jx
```
