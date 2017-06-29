### Prepare you Laptop for Particle Dev 
1. [Install Node onto your system](https://nodejs.org)
1. Install particle CLI `npm install -g particle`
1. [Install dfu-utils](http://dfu-util.sourceforge.net/)
### Compile & upload via
1. [Put particle board in DFU mode](https://docs.particle.io/guide/getting-started/modes/photon/#dfu-mode-device-firmware-upgrade-)
1. Create Program (e.g. foo.ino)
1. Compile & Upload program using particle CLI
    ```
    particle compile photon foo.ino --saveTo foo.bin
    particle flash --usb foo.bin
    ```
