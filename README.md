In the file names SITE 1, the Master Repeater must be at 192.168.1.2:50000. There are two peers at SITE 1: Peer1 192.168.1.3:50001 and Peer2 192.168.1.4:50002.
The Rest Channel/Site IP must be 192.168.1.100:55000 at both (all) sites.
IP Remote Programming is also possible but the Device programmer must be configured to use TCP ports 50000 to 50100 (which ought to be the default).

The file SITE 2 is almost the same but there are only two peers: Peer3 192.168.1.2:50003 and Peer2 192.168.1.3:50004.
Since SIT1 and SIT2 are in two different physical subnets, the 192.168.1.0/24 addresses can be reused at each site.

The WAN IP of the SITE1 Router is 10.0.0.1 and for SITE2 it is 10.0.0.1 -  these should be changed to suit your network.

Both Routers have a small block of DHCP addresses in the range between .200 and .254.
