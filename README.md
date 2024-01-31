# Pi-sane
A Raspberry PI turning a USB scanner into a network scanner with:
- An old [Raspberry PI 3B v1.2](https://www.raspberrypi.com/products/raspberry-pi-3-model-b/) running [Raspberry PI OS Lite](https://www.raspberrypi.com/software/operating-systems/#raspberry-pi-os-32-bit)
- The [SANE](http://www.sane-project.org/) software in the [Debian libsane1](https://packages.debian.org/bookworm/libsane1) package
- A [Canon Canoscan LiDE 400](https://www.canon.co.uk/business/products/scanners/flatbed-scanners/canoscan-lide-400/) USB scanner

I'll be using the [Scanner page in the Debian Wiki](https://wiki.debian.org/Scanner) as my guide
and document my progress here ...

## Notes
When everything is working okay, change the SD-card to read-only mode to prevent corruption:
- https://core-electronics.com.au/guides/read-only-raspberry-pi/
- https://learn.adafruit.com/read-only-raspberry-pi/overview
- https://github.com/anschwa/raspberrypi-readonly-filesystem
- https://blockdev.io/read-only-rpi/
- https://blockdev.io/easy-changes-on-a-read-only-raspberry-pi/
- https://github.com/awawa-dev/HyperHDR/wiki/Raspberry-Pi-OS-read-only-mode
