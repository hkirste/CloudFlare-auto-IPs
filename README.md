CloudFlare-auto-IPs v0.1
===================

Automaticlly update your server's firewall to allow CloudFlare IPs

Features:
Works with CSF and IPtables
Runs each day checking for new CF IPs to add

How to install:

wget https://raw.github.com/hkirste/CloudFlare-auto-IPs/master/cf.sh
sh cf.sh

This will setup the script in your server for to run each day checking for new IPs to add.
