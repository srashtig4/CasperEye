# CasperEye 
Advance Recon Tool 
---
					                         version: 1.0  	          
  ▄▄                          	  ▗▄▄▄▖          
 █▀▀▌                         	  ▐▛▀▀▘          
▐▛    ▟██▖▗▟██▖▐▙█▙  ▟█▙  █▟█▌▐▌   ▝█ █▌ ▟█▙ 
▐▌    ▘▄▟▌▐▙▄▖▘▐▛ ▜▌▐▙▄▟▌ █▘  ▐███  █▖█ ▐▙▄▟▌
▐▙   ▗█▀▜▌ ▀▀█▖▐▌ ▐▌▐▛▀▀▘ █   ▐▌    ▐█▛ ▐▛▀▀▘
 █▄▄▌▐▙▄█▌▐▄▄▟▌▐█▄█▘▝█▄▄▌ █   ▐▙▄▄▖  █▌ ▝█▄▄▌
  ▀▀  ▀▀▝▘ ▀▀▀ ▐▌▀▘  ▝▀▀  ▀   ▝▀▀▀▘  █   ▝▀▀ 
	       ▐▌                     █▌ 
***

# Usage

``` ./casperEye.sh target-Website OR casperEye.sh target-Website ```
 
To Enable Nmap use: 
 casperEye.sh target-Website -nmap
 

 # About
 CasperEye is a script written in Bash, it is intended to automate some tedious tasks of reconnaissance and information gathering. This tool allows you to gather as much as information about the target and helps uncovering huge numbers of subdomains and other juicy information.


 # Main Features
 - Create a dated folder with scan results
 - Grab subdomains using:
	1. certdata-api
	2. crt.sh API
	3. certspotter API
	4. assetfinder
	5. Subfinder 
	6. Aquatone
	7. Sublist3r
	8. Knockpy
	9. Hackertarget API
	10. Subbrute
	11. Dig Linux tool [ For Ip Digging ]
	12. Rustscan [ Scan All Open Ports ]
	13 .Nmap [ Scan All Runing Services on Port ]
	14. Httprobe [ Provide all Live Url's]
 
- WayBack URL Machine 
- SSRF Juicy Link Finder 
- Creating target specific wordlist
- Generating Seprate HTTP Response Code
- Supports ProtonVPN 
- **Sending Telegram Alert with Complete Final Recon File**
- Fetch All Target Ips
- You can Enable Nmap with Rustscan ,will Give You all open Port with All Running Services On target Ip
- Easy To use [ Only Enter target Domian and then it will Alert you with Recon File ]


# Installation & Requirements
- Download and install the script from https://github.com/hacker50120/CasperEye

### ``` ./casperEye-installation.sh ```
Go version 1.10 or later.

# Setup Telegram Alert Notifier
Steps: 
1. Search BotFatherin telegram App
2. Start Your Bot with ``` /start```
3. Select ```/newbot```
4. Enter the Name for Your Bot
5. Genrate Your Telegram Bot Token ``` /token ```
6. Then Enter Your Bot_API And ChatID in ```set-api-keys.sh```
``` Bot_api="$$" ```
``` chatID="$$" ```

### How to Get ChatId:
Add That Bot in the Gropu With You.
then Send "Hi" in the Group
After Than Go to terminal and 
```curl https://api.telegram.org/$$YOUR_API_TOKEN/getUpdates ```
You will Get ChatID of your Telegram Account.

## System Requirements
	Recommended to run on vps with 1VCPU and 2GB ram.

# Authors and Thanks
 - https://github.com/tomnomnom
 - https://github.com/projectdiscovery/subfinder
 - https://github.com/michenriksen/aquatone
 - https://github.com/aboul3la/Sublist3r
 - https://github.com/guelfoweb/knock
 - https://github.com/TheRook/subbrute
 - https://github.com/RustScan/RustScan
 - https://protonvpn.com/
 
# TO DO
Some New Feature will add soon.

## Warning: 
This code was originally created for personal use, it generates a substantial amount of traffic, please use with caution.
