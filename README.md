# Netmiko for OSPF & DHCP Automation
Configure IP Address, DHCP Server and OSPF automatically using Netmiko

This repository contains two script to configure IP Address, DHCP Server, and OSPF automatically using Netmiko. The first script is inventory.yml that contains data about the router, and the second script is Python script to doing automation. 

You can automate OSPF & DHCP Configuration with differents topology using this script. You just need to edit the inventory.yaml to meet the topology that you have.

<h3>Requires</h3>
<ul>
  <li>netmiko==2.2.2</li>
</ul>
<h3>Supports</h3>
<ul>
  <li>This script support for Cisco IOS</li>
</ul>

<h3>How to use</h3>
<ul>
  <li>Ensure you setup the topology</li>
  <li>Configure Management IP Address and enable SSH in the router</li>
  <li>Edit the inventory.yaml to meet your topology</li>
  <li>Run the script <i>python3 script.py</i></li>
</ul>
