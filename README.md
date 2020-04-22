# Ansible for Raspberry Pi

This is a simple repo to setup my Raspberry Pi with all the things I need

## PreRequisites

You need to have ansible and Git installed in your Raspberry Pi

```
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install git ansible -y
```

## Usage


```
git clone https://github.com/nelsonyaccuzzi/ansible-rpi.git
cd ansible-rpi
ansible-playbook main.yml
```
