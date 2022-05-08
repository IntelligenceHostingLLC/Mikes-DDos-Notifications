# Mikes-Notifications


### Installiation (tested with ubunutu 20) (all steps)
apt install python3-pip
apt install tcpdump
apt install tshark

pip3 install psutil

pip3 install discord_webhook

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.muylinux.com%2Fwp-content%2Fuploads%2F2020%2F05%2FUbuntu2004LTS.png&f=1&nofb=1" />




<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmiro.medium.com%2Fmax%2F2400%2F1*0Cnn6fwW1IKqekwRP_nGIg.jpeg&f=1&nofb=1" />

### Installing and Configuring Openvpn
wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh

Protcol [1]: 1 (You can make this whatever)

Port [1194]: 1194 (You can make this whatever

DNS server [1]: 1 (You can make this whatever)

Name [client]: Snoop (you can make this whatever)

#### Configuring

go to /etc/openvpn/server/server.conf 

change the verbosity to 4

add the status log to the main openvpn directory

Connect after you added all these configurations

### reboot server -- important

Add these to server.conf:

verb 4  

status openvpn-status.log 

log-append  openvpn.log




### JSON Docs

Webhook uses discords intergrated webhooks to display the notifications as a bot_nat-type
Users: This shows the discord bot Username so if you want it Gorilla it will be called Gorilla as the bot username
Serverheader: Displays the topmost header of IP I would recommend having this as your hostname
Title: Displays at the topmost of the screen the text of the ddos notifications at the top
Description: Additive to the title shows the text below the bottom of the title header
Color: Uses decimal format on color type have this to change hte discord notis color
Footergif: Shows the footer animated circle
License: License just so we can verify you through our api system
Image: Sets it by the title the image to right of the title.
Url: Will add a clickable link to the title header
Banner: Shows the animated banner at the bottom showing the feautures
Footer: Add custom footer text to the ddos notifications




### Feautures
Completely Custom
IP
Location
Uptime
Serverload
Packet Count
Uptime
Attack Types
Incident ID
Auto PCAP
Openvpn Conneccted Users (numeric value)
Openvpn Users Online 
Spoofing
Banner

<img src="https://media.discordapp.net/attachments/968000706852294666/972754559124537344/standard_1.gif" />


### Compatible with Git
To make this possible we added a git function because some string arrays might mess up in regular unicode:
git https://github.com/IntelligenceHostingLLC/Mikes-Notifications.git

<img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Flinoxide.com%2Fwp-content%2Fuploads%2F2015%2F03%2Fgithub-universe.jpg&f=1&nofb=1" />


### Photo of these notifications

<img src="https://i.ibb.co/TKqpHkK/lmaoxd.png" />
