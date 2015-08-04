# rpi
rpi-tor-agent
Raspberry tor agent -(tor:Martin Vojtíšek)



description:

tor hidden service based introduction agent




info:

raspberry will be placed to victims wifi network -(it can stay wifi shutdown/reset or lose of the connection )

tor based tunneling attacker<--->tor<--->rpi(hidden service  sever) (hidden service based)



usage:
anonymous inter network introduction, proxy or vpn exit point)



advantages:

+anonymity 

+tor can bypass most ids or ips -(can be used on great secured networks or at  networks with public ip inaccessible (nat ISP :-(  ) 

+can stay wifi shutdown/reset or lose of the connection (aggressive connecting) and other forms of interruption




disadvantages:

-tor isn't too much silent

-pig codet (security obscurity) 




requirements:

wpa_supplicant and tor (Linux command line version installed)

tor hidden service configured https://www.torproject.org/docs/tor-hidden-service.html.en

configured wpa_supplicant.conf at /etc/wpa_supplicant.conf http://www.blackmoreops.com/2014/09/18/connect-to-wifi-network-from-command-line-in-linux/

the scripts con-status ,wifi-connect ,con-wifi ,con-start placed at /usr/share/con-auto (con-auto dir must be created)

the con-auto must be at /etc/init.d and run on startup of the raspberry





recommendation:

raspberry running with kali linux (tested )

using ip bridges on tor

maybe some fragmentation of packets will be good


