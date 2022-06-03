# esxi-7.0.2-Ansible-Deployer
This Ansible Playbook Auto Deploys a DHCP version of vSphere ESXi 7.0.2 to a group of iLO based ProLiant Servers.

To run this playbook please edit the host file and put your iLO targets. The SSH based Ansible playbook will execute raw SSH commands on the iLO. This is a great simple method to get started with HPE iLO ProLiant scripting because it does not require Python or any server side modules or packages.

1. Edit Host file with target iLOs
2. Confirm you can pull the kickstarted ISO from a web server
3. run this command from the directory where you pull down the host file and the main playbook (ansible-playbook -i ilohosts iLO-sshVirtualMedia_1.2.yaml --ask-pass)
4. When prompted enter the iLO password.

ENJOY! , Robert Ryan
