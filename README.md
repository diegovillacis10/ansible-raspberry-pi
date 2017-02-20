# Ansible Playbooks for Raspberry Pi

Some ansible configurations for the Raspberry Pi.

### Getting started:

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

### Special thanks to:
- [James Barwell](https://github.com/JamesBarwell)
