# klipper-printer-configs
Configuration for Voron v2.4r2 3d printer.

## Installation

1) Login to printer and switch to the home directory:

```
cd ~
```

2) Clone repository: 

```
git clone --branch red-voron-2.4 https://github.com/adamhogle/klipper-printer-configs.git
```

3) Switch from old config to new config:

```
mv ~/printer_data/config ~/printer_data/config.old
ln -sf ~/klipper-printer-configs/config ~/printer_data/config
ln -sf ~/mainsail-config/mainsail.cfg ~/printer_data/config/mainsail.cfg
```

## Updating

```
git pull -f
```
