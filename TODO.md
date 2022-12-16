# To Do

# Define base image for Proxmox Virtual Environment

## In Ansible
* Setup up name and IP address for machine  // This maybe done during install.
* Remove Subscription Message
  * sed -Ezi.bak "s/(Ext.Msg.show\(\{\s+title: gettext\('No valid sub)/void\(\{ \/\/\1/g" /usr/share/javascript/proxmox-widget-toolkit/proxmoxlib.js && systemctl restart pveproxy.service
* SSL Certificate
  * Generate Cert
  * Install Cert
    * See http://xwiki.home.arpa:8080/xwiki/bin/view/Proxmox%20Tips%20and%20Tricks/  Installing HTTPS Certificate


# Define base image for ubuntu server

## In Ansible
* Setup up name and IP address for machine // this maybe done during install.
* Setup LDAP Client
* Install Root Certificate for HTTPS connections
* Setup Ansible configuration.
* Setup Qemu-guest-agent
  
