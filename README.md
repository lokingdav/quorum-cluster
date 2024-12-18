# Quorum Setup with N nodes
Make sure you change the IP address  of the nodes in ```inventories/hosts.yml```.

## Run Playbook
Run in the root of this repository
```bash
ansible-playbook -i inventories/hosts.yml site.yml
```