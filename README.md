# Ansible Playbook for Deploying Elasticsearch

This Ansible playbook automates the deployment of Elasticsearch, an open-source search and analytics engine, on target servers. It will install Elasticsearch, configure necessary settings, and start the Elasticsearch service.

## Prerequisites

Before running this playbook, ensure the following:

1. Ansible is installed on your local machine.
2. You have SSH access to the target servers with appropriate privileges.
3. You have knowledge of the Elasticsearch version and configuration requirements for your use case.

## Instructions

1. Create an inventory file named `inventory.ini` and specify the target hosts in it, Update the `hosts` in the Ansible playbook.  
2. Set the `ES_URL` variable to the desired Elasticsearch Package.

## Running the Playbook

1. Save the playbook in a file named `install_es.yaml`.
2. Create an inventory file named `inventory.ini` and specify the target hosts in it.
3. Execute the following command in the terminal:

```bash
ansible-playbook -i inventory.ini install_es.yaml
```

