# Blueprint-TD110D-Linux-Driver-Workaround

## Ini adalah catatan workaround saya untuk menggunakan printer Blueprint TD110D pada OS Linux
### Tested on MX-Linux Live

Dependencies:
- libscupsimage2 - on Ubuntu/Debian based
- libxcrypt-compat - on ArchLinux

## Driver yang digunakan diambil dari driver printer HT300 (Linux TSPL Drivers for HT300/HT330)
### https://www.hprt.com/hprt/files/product_down_file/model/31/classify/42.html

- Extract Driver
    - tar -cf HT300-LINUX-DRIVER.tar
- gunakan perintah sudo ./install

setting printer via cups atau printer manager lainnya
- Koneksikan printer via USB
- Add new printer
- Pilih Blueprint Printer
- Provide PPD file
- Browse ke folder PPD, pilih HT300
- Print Test Page, it should be working now
