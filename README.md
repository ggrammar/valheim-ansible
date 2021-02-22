# ansible-valheim

Install a dedicated Valheim server with Ansible!

Based on https://developer.valvesoftware.com/wiki/SteamCMD and https://gameplay.tips/guides/9765-valheim.html 

This repo is a work in progress. 

### How to Use
 - Create an "inventory" file that lists your servers, and the user that will connect. `server-name ansible_user=whoever`
 - Install steamcmd (manual step for now)
 - `ansible-playbook -i ./inventory ./site.yml`

### TODO
 - Variable support for name, world name, password
 - Template out start\_server.sh, with port variable
