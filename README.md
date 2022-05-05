# ansible-wireguard-management
Ansible configs for Wireguard management

# Usage
```bash
sudo ansible-playbook wg-add.yml --extra-vars "clientName=Franta clientIp=10.10.10.5 clientMask=24 clientDNS=1.1.1.1 workDir=./userName serverIp=<<your server ip>>"
```
