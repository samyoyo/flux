#Fluxion is the future
Fluxion is a remake of linset by vk496 with less bugs and more features. It's compatible with the latest release of Kali (Rolling)

## :scroll: Changelog
##### 17/09/2016:
---
* Update from upstream
* Add adb epicentro template
* New auto-update script

##### 01/07/2016:
---
* Update from upstream

##### 30/04/2016:
---
* First release with template page


## :octocat: How to contribute
All contributions are welcome, from code to documentation, to graphics, to design suggestions, to bug reports.  Please use GitHub to its fullest-- contribute Pull Requests, contribute tutorials or other wiki content-- whatever you have to offer, we can use it!
## Chat
[Invite] (https://discordapp.com/invite/0i2gj5uQ6RH9XYx5)

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

Nothing to configure! Just follow these steps:
* Press "[Download ZIP](https://github.com/DidyMond/fluxion/archive/master.zip)"
* Unzip the file
* Enter into extracted directory
* Run `sudo ./Installer.sh` to be sure you have all the updated script
* Finally, to launch the program: `sudo ./fluxion`

##  :question: Which template are contained?

* Adb Epicentro
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
* Capture a handshake (can't be used without a valid handshake, it's necessary to verify the password)
* Use WEB Interface *
* Launch a FakeAP instance to imitate the original access point
* Spawns a MDK3 process, which deauthenticates all users connected to the target network, so they can be lured to connect to the FakeAP and enter the WPA password.
* A fake DNS server is launched in order to capture all DNS requests and redirect them to the host running the script
* A captive portal is launched in order to serve a page, which prompts the user to enter their WPA password
* Each submitted password is verified by the handshake captured earlier
* The attack will automatically terminate, as soon as a correct password is submitted

##  :heavy_exclamation_mark: Requirements

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

A linux operating system. We recommend Kali Linux 2 or Kali 2016.1 rolling. Kali 2 & 2016 support the latest aircrack-ng versions. A external wifi card is recommended. 

## Useful links
 1. [wifislax] (http://www.wifislax.com/)
 2. [kali] (https://www.kali.org/)
 3. [linset] (https://github.com/vk496/linset)
 4. [ares] (https://github.com/deltaxflux/ares)

## Disclaimer

***Note: Fluxion is intended to be used for legal security purposes only, and you should only use it to protect networks/hosts you own or have permission to test. Any other use is not the responsibility of the developer(s).  Be sure that you understand and are complying with the Fluxion licenses and laws in your area.  In other words, don't be stupid, don't be an asshole, and use this tool responsibly and legally.***
