# my_linuxcnc_hall
Hall files for my pm25 cnc mill

`Flash a clean SD card with the linixcnc image or build from sorce.
*Note, if using prebuilt image, you may need to open configuration file to turn on screen brightnes.
For some reson this is commited out by defualt
`

``After booting the Pi, set up static IP``
```
sudo nano /etc/dhcpcd.conf
```
```
interface eth0
static ip_address=10.10.10.5
static ip6_address=<__________________________________>
static routers=<_____________>
static domain_name_servers=<________________>
```
``
After reboting, this should ping as 10.10.10.10
``

``

`
Upgread linuxcnc:
`

```
sudo apt-get install linuxcnc-uspace
```

From here, use the pfcofig tool to set up static ip
``
******************************************************************************************************************
``Pin out``


``
I am using a 7i96s and 4Gb Pi4
``

``
7i96s docs: http://www.mesanet.com/pdf/parallel/7i96sman.pdf
``