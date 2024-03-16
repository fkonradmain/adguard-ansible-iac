# Adguard-Ansible-IAC

This machine was bought on ionos at 2024-02-02.

## Core Data of the current Instance

Validity: 1 Year
Location: USA
ASN: 54548
OS: Debian12

## Ansible User

The first user is the ansible user

## Ansible Vault Mapping

Key Mapping: `default@.default_vault_pass.txt` - this is configured in ansible.cfg

cd to ansible/

set up the key as the file ansible

## Git submodules

The ansible galaxy modules are present as git submodules

To automatically update the submodules to the latest tags avaiable, run:

```bash
git submodule foreach \
'git fetch origin; git checkout $(git describe --tags `git rev-list --tags --max-count=1`);'
```

if you have custom changes to the submodules, you probably should not
run that command because it will pull the latest tags and not the latest
content of your branch or fork.
