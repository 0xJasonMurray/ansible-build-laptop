# Overview

Ansible playbook to configure my laptop.

Besides the Google and Box drive configuration the vast majority of the configuration should work for almost anyone.  (See #Post Configuration below for extra details)

These are the tools I use as a systems and network architect.


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

# Post Configuration

I use Google Drive for personal files and Box Drive for business file storage.

Both of these systems need to be manually configured after installation.
