# grafana-setup
## To set up 
* Make sure your computer have already install ansible
* Make sure you have add ssh key to your VM
* Config inventory point to your IP address
## Command
### Install grafana
```sh
   ansible-playbook -i inventory grafana-playbook.yml
   ```
