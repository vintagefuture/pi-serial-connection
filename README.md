# pi-serial-connection

I recently discovered a very cool method to connect to my Pis, that doesn't require the complications of SSH: **serial connection**.

In its simplest form, you connect **GROUND RXD0 TXD0** pins as follows:




On a Linux terminal, make sure you have `screen` installed, then run:

```
sudo screen /dev/ttyUSB0 115200
```
