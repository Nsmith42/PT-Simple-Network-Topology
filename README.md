Simple Network Topology Documentation

Switches:
Switch 1 – 3650-24PS Cisco Switch
  -	PoE+ Supported – 30 Watts per port
  -	Interface range - GigabitEthernet1/0/1 - GigabitEthernet1/0/24
  -	Required power supply to be inserted into switch – to turn switch on

User Devices: 
-	Laptop 1
  -	Connected to Switch 1 via Copper ST ethernet cable
    -	Connected via FastEthernet0 (Laptop 1) to GigabitEthernet1/0/1
    -	Static IP - 192.168.1.1
    -	Subnet Mask - 255.255.255.0
    -	MAC address - 0001.C9E5.BCDD
    -	Default Gateway - 192.168.1.254
    -	DNS Server – 8.8.8.8 (Google)
-	Laptop 2
  -	Connected to Switch 1 via Copper ST ethernet cable
    -	Connected via FastEthernet0 (Laptop 2) to GigabitEthernet1/0/2
    -	Static IP - 192.168.1.2
    -	Subnet Mask - 255.255.255.0
    -	MAC address - 000B.BEDC.D990
    -	Default Gateway - 192.168.1.254
    -	DNS Server – 8.8.8.8 (Google)

Notes:
-	Depending on laptop model and age, you can connect with USB-C/USB-to-Ethernet adaptor or built-in ethernet interface on laptop
-	In this demonstration, devices do not have a dynamic IP address
-	Pinging either Laptop 1 or Laptop 2 results in a Reply



