## What is this?
This repository stores the Ansible variables that contain all the credentials needed to run an Open Food Network instance and it's meant to be used from and within https://github.com/openfoodfoundation/ofn-install
## Provisioning
```shell
~/ofn-install $ ansible-playbook playbooks/production.yml --limit=us-prod -e "@../ofn-net-secrets/production.yml" -i inventory/hosts --ask-vault-pass
```
