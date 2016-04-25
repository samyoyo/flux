#Fluxion is the future
Fluxion is a remake of linset by vk439 with fixed bugs and added features. It's compatible with the latest release of Kali (Rolling)

## :scroll: Changelog
Fluxion gets updated weekly with new features, improvements and bugfixes. 


## :book: How it works

* Scan the networks.
* Capture handshake (can't be used without a valid handshake, it's necessary to verify the password)
* Use WEB Interface
	* Some standard pages
	* Some real pages of routers 
* Launches a FakeAP instance imitating the original access point
* Spawns a MDK3 processs, which deauthentificates all of the users connected to the target network, so they can be lured to connect to FakeAP network and enter the WPA password.
* A DHCP server is launched in FakeAP network
* A fake DNS server is launched in order to capture all of the DNS requests and redirect them to the host running the script
* A captive portal is launched in order to serve a page, which prompts the user to enter their WPA password
	* Real pages simulate a firmware update 
* Each submitted password is verified against the handshake captured earlier
* The attack will automatically terminate once correct password is submitted

##  :question: How configure template?

still working

##  :question: Which template are contained?

* Alice
* Asus
* Belkin
* Cisco
* Cisco Linksys
* Digicom
* Dlink
* FritzBox!
* Huawei
* Netgear
* Netis
* Sitecom
* Technicolor
* Telecom
* TPLink
* Zyxel



##  :heavy_exclamation_mark: Requirements

A linux operating system. We recommend Kali Linux 2 or Kali 2016.1 rolling. Kali 2 & 2016 support the latest aircrack-ng versions. A external wifi card that supports packet injection is recommended.


##  :eight_spoked_asterisk: Bugs fixed
- [x] Negative Channel
- [x] Kali Patch for Kali Patch 2 
- [x] Added airmon 
- [x] Translate DE --> EN
- [x] Handshake get fixed 
- [x] Animations
- [x] Wifi List Bug 

## :octocat: Credits
1. DidyMond main developer for this project
2. Deltax @FLuX and Fluxion main developer for original project 
3. Strasharo @Fluxion help to fix DHCPD and pyrit problems, spelling mistakes
4. vk439 @Linset main developer of linset 
5. ApatheticEuphoria @Wifi-Slaughter WPS Crack 
6. Derv82 @Wifite/2 
7. Sophron @Wifiphisher
8. sensepost @Mana