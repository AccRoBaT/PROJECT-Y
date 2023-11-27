# PROJECT-Y
Simple explanation and overview of multiple server DoS/DDoS defense mechanism.


To test out how everything works you will need a VM of any linux distro (Im using ubuntu 22.04) for each folder in the .rar file.

----------------

My presentation was made by this:
2 laptops.

laptop 1:
Set a static IP addres 192.168.1.1, subnet 255.255.255.0

laptop 2:
Set a static IP address 192.168.1.2, subnet 255.255.255.0

(Connect them with Ethernet cable LOL)

----------------

Set each of your VMs ips to 192.168.1.100, ...101, ...102
After that install apache2, python3 (along with the libs needed), screen. (dont forget to ulimit everything to ulimited)
Run every executable on a sepparate screen.

You are done! Feel cool! :)
