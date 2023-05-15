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
From here, use the pfcofig tool to set up static ip
``
******************************************************************************************************************
