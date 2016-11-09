net/sc.sniffhttp module for Katana
========================================

Module for sniffing HTTP traffic and finding PWD's, cookies, etc.

Katana/modules/net/sniff_http.py

## Requirements
* [Katana](https://github.com/PowerScript/Katana)

## The script
 The script uses scapy to work with the packages. Regex is used for finding info.
 The main purpose is to extract password and username from packets.
 
### Regex
   The regex is for password looking for pass and pwd. Adjust appropiated.

## Installation
 For adding module: sudo python2 ktf.ktf --i-module path/to/file/without/file/extention
 
License
-------

MIT, 2016 Thomas TJ (TTJ)

Other
-----

Want to try it without Katana? Test it with python3 here [scapy_sniff_http](https://gitlab.com/ThomasTJ/scapy_sniff_http)
