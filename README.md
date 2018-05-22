# Ansible Playbooks for Raspberry Pi

Some ansible configurations for the Raspberry Pi.

### Requirements:
  - [Ansible](https://docs.ansible.com/ansible/2.4/intro_installation.html)

### Getting started:

Edit the `inventory` file and updated with the IP of you Raspberry Pi.

#### Wifi Role

Change the `group_vars/all` file so you replace the variables with the information of your network
For example:

```
# wifi
wifi_ssid: my_wifi_name
wifi_pass: mySup3rp@ssw0rd
```

Then, execute the playbook.

#### Retropie Role

Just execute the playbook. Roms will have to be provided by you 😉

```sh
$ ansible-playbook retropie.yml -i inventory
```

### Special thanks to:
- [James Barwell](https://github.com/JamesBarwell)
