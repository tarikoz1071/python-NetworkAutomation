# python-NetworkAutomation
# Reviewed on 2th of August 2023

Prerequisites:
Properly fill **switch_information.txt** file with proper IP addresses, username and password information to connect each address.
No upper limit tested for maximum ssh connection. But as a reference, my project was about 20 connections and took 7 seconds to finish on a Local network.
Below is an example for the content of this file:

192.168.1.1 Netwobserver 0bs3rv.M@n!

In here, "192.168.1.1" is the IP address, "Netwobserver" is the username and "0bs3rv.M@n!" is the password.

Once this file is filled up correctly, the script is ready for scanning access interfaces on which VLAN 100 can pass.

