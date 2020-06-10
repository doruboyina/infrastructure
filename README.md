# Ameelio infrastructure

Infrastructure provisioning and management scripts for Ameelio services.
Unless you are managing infrastructure for Ameelio, these scripts are
not intended to be used directly.  You can however use them as examples
or a starting point for bootstrapping your own infrastructure.

## Technologies involved

This repository makes use of [Terraform](https://www.terraform.io/) and
[Ansible](https://www.ansible.com/) for provisioning/maintenance.

Terraform is used for immutable infrastructure, and currently provision:

1.  Digital Ocean managed Kubernetes Cluster
1.  Digital Ocean MySQL managed database
1.  Backblaze Cloud Object storage


- MySQL
- K8s
- Backblaze

## Using the Automation

Before you are able to run any of the scripts here, you will need to have
Ansible and Terraform installed.  Please consult the documentation for
those tools and your chosen operating system.
