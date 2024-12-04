# sip-server-configuration [Project time: Jul 2024 to August 2024]
<br>I successfully installed and configured Ubuntu latest Server OS on a dedicated server using a live bootable USB drive, set up RAID and installed Asterisk to create a SIP server for remote audio codec connections. I customized the `sip.conf` and `extensions.conf` files to meet specific audio transmission requirements, utilizing my advanced Linux skills for server management and troubleshooting. By setting up the SIP server, the need for a VPN was eliminated, resulting in a fully functional system that enabled seamless remote audio communication. This project demonstrated my strong problem-solving abilities and technical expertise in Linux and server management.</br>

<br>
Contents of this Repo:
<br>a)Two sip server config files</br>
    b)One readme file</br>
We need to create specific extensions and passwords for the remote clients in the sip server.Then configure remote clients with these extensions,passwords also specify remote sipservers DDNS hostname to reachout to the server.
The sip server is in DMZ.Once the clients are online they will try to register themselves with the sip server, if extension and password matches then the sipserver will register the remote clients.Then you can dial from one remote codec to another using respective extension without using VPN.Also the sipserver is intermediary.</br>
