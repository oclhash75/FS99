# FS99 THE IMPROVED REDHAWK
#### Version 2.0.0
#### By R3D#@0R_2H1N A.K.A Tuhinshubhra
All in one tool for **Information Gathering** and **Vulnerability Scanning**

# Scans That You Can Perform Using FS99 :
+ Basic Scan
	- Site Title **NEW**
	- IP Address
	- Web Server Detection `IMPROVED`
	- CMS Detection
	- Cloudflare Detection
	- robots.txt Scanner
+ Whois Lookup `IMPROVED`
+ Geo-IP Lookup
+ Grab Banners `IMPROVED`
+ DNS Lookup
+ Subnet Calculator
+ Nmap Port Scan
+ Sub-Domain Scanner `IMPROVED`
	- Sub Domain
	- IP Address
+ Reverse IP Lookup & CMS Detection `IMPROVED`
	- Hostname
	- IP Address
	- CMS
+ Error Based SQLi Scanner
+ Bloggers View **NEW**
	- HTTP Response Code
	- Site Title
	- Alexa Ranking
	- Domain Authority
	- Page Authority
	- Social Links Extractor
	- Link Grabber
+ WordPress Scan **NEW**
	- Sensitive Files Crawling
	- Version Detection
	- Version Vulnerability Scanner
+ Crawler
+ MX Lookup **NEW**
+ Scan For Everything - _The Old Lame Scanner_

---
# Released Versions:
    - Version 1.0.0 [11-06-2017]
    - Version 1.1.0 [15-06-2017]
    - Version 2.0.0 [11-08-2017]

# Changelog:
- Version 1.0.0
    - Initial Launch
- Version 1.1.0
    - Updated The `fix` command
- Version 2.0.0
	- Separated all scans so that you are served the amount of information you need
	- `Sub-Domain Scanner` improved
	- `fix` command improved
	- `Web Server Detection` Improved
	- `CMS Detection` Improved
	- `Banner Grabbing` Improved
	- Added `WordPress Scanner`
	- Added `Bloggers View`
	- Added `MX Lookup`
	- Added `Update` option
	- RED HAWK Banner Updated
	- Many Other Internal Fixes

# Installation:
1. Run The Tool and Type `fix` This will Install All Required Modules.
2. For The Bloggers View To Work Properly you have to configure FS99 with moz.com's api keys for that follow the following steps:

# Usage:
- git clone `https://github.com/oclhash75/FS99`
- cd FS99
- php FS99.php
- Use the "help" command to see the command list or type in the domain name you want to scan (without Http:// OR Https://).
- Select whether The Site Runs On HTTPS or not.
- Select the type of scan you want to perform
- Leave the rest to the scanner

# List of CMS Supported
RED HAWK's `CMS Detector` currently is able to detect the following CMSs (Content Management Systems) in case the website is using some other CMS, Detector will return _could not detect_.

- WordPress
- Joomla
- Drupal
- Magento
# Known Issues
**ISSUE:** Scanner Stops Working After Cloudflare Detection!

**SOLUTION:** Use The `fix` Command OR Manually Install *php-curl* & *php-xml*



# Suggestions And Feedbacks
Want to contribute to RED HAWK or point out something wrong? Just create a new issue here: https://github.com/Tuhinshubhra/RED_HAWK/issues/new
I'd love to hear from you.

# TODOs

- Make a proper update option ( Installs current version automatically )
- Add more CMS to the detector
- Improve The WordPress Scanner ( Add User, Theme & Plugins Enumeration )
- Create a web version of the scanner
- Add XSS & LFI Scanner
- Improve the Links grabber thingy under bloggers view
- Add some other scans under the Bloggers View
