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

## Ansible Galaxy Modules

The ansible galaxy modules will have to be installed manually.
They can be found by looking through `ansible/playbook.yml`.
As of 2024-02-18, all referenced roles will have to be pulled
from ansible-galaxy.

Be aware: the onkeldom.adguard_home module must be
the current master branch version, not the one on ansible.
