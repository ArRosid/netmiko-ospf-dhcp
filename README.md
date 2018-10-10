# Netmiko for OSPF & DHCP Automation
Configure IP Address, DHCP Server and OSPF automatically using Netmiko

This repository contains two scripts to configure IP Address, DHCP Server, and OSPF automatically using Netmiko. The first script is inventory.yml. It contains data about the router. The second script is a Python script that performs the automation. 

You can automate OSPF & DHCP Configuration with differents topologies using this script. You just need to edit the inventory.yaml to align with the topology that you have.

<h3>Requires</h3>
<ul>
  <li>netmiko release 2.2.2 or later (tested with release [2.2.2](https://github.com/ktbyers/netmiko/releases/tag/v2.2.2))</li>
</ul>
<h3>Supports</h3>
<ul>
  <li>This script supports Cisco IOS network devices (e.g. router, switch)</li>
</ul>

<h3>How to use</h3>
<ul>
  <li>Ensure you setup the topology</li>
  <li>Configure Management IP Address and enable SSH in the network device</li>
  <li>Edit the inventory.yaml to align with your topology</li>
  <li>Run the script <i>python3 script.py</i></li>
</ul>
