# Freeze BIOS
A new bootloader for Computercraft

---

### Features

 * Supports multiple operating systems (including CraftOS!)
 * Installs your current version of CraftOS
 * Runs on top of shell (no more annoying rednet coroutine)
 * Fully sandboxed operating systems (even the installer gets sandboxed when ran)
 * Allows you to install OSes from disk
 * Startup disks won't work, and installing from them will only affect their sandboxed environment (secure system)
 * Password-protected: no more pesky rivals messing with your settings
 * Disks work accross all OSes
 * Contains a built-in auto-updater

### Planned Features

 * Fix fs.find and fs.complete not working for mounted paths
 * Installer API so that installers can set certain special settings (maybe even automatically set the OS name, etc)
 * Install from GitHub support
 * Better OS setup menu
