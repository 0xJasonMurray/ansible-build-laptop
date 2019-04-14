# Overview

Ansible playbook to configure my laptop.

# Prerequisites

Install Ansible: `pip install ansible`

# Running

## All tasks:
`ansible-playbook build-laptop.yaml --ask-become-pass`

## Specific Tags
`ansible-playbook build-laptop.yaml --ask-become-pass --tags homebrew`

## Available Tags:
* homebrew
* casks
* pip
* clouddrive
