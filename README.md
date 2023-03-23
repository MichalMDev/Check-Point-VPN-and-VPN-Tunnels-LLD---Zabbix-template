# Check-Point-VPN-and-VPN-Tunnels-LLD-Zabbix-template
Fork of https://github.com/zabbix/community-templates/tree/main/Network_Appliances/template_checkpoint_vpn-1 with added LLD VPN tunnel detection from json file

Copy cp_vpn_list.sh and cp_vpn_list.json to /usr/lib/zabbix/externalscripts/
Then run:

cd /usr/lib/zabbix/externalscripts/

chown zabbix:zabbix cp_vpn_list.json cp_vpn_list.sh

chmod +x cp_vpn_list.sh cp_vpn_list.json

Then import the template to zabbix server. Fill te json file, and link template to the host.
