# Chroot environment for CraftOS 1.7

These few scripts allow to securely switch to new root on the computer in order to run programs or the whole OS in sandbox. The most importan API calls have beend rewrittend to make this secure. Also, bios.lua file has been reworked. It is possible to pass the native API functions like setAlarm without re-implementing them.

### Usage
1. Create chroot using mkroot command. bios.lua file has to be in the same directory.
2. Change to the new root using chroot command.

### TODO
1. Fix some unexpected bugs

### Contributions
Lymia - the actual code was written by him/her, but was modified to support newer CraftOS versions.
Dan200 - for writing the bios.lua file, it was taken from computercraft 1.74 jar file. I have modified the program to work in chroot.
