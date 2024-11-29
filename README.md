# gs_usb kernel driver

Clone this repository under `/usr/src/gs_usb-5.15`.

## Install using dkms

To see which modules are installed on your system use `dkms status`

Follow these steps to install:
- `dkms add -m gs_usb -v 5.15`
- `dkms build -m gs_usb -v 5.15`
- `dkms install -m gs_usb -v 5.15`
