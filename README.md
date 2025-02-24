# Ansible Pull Demo

This demo shows how to utilize 3rd party Ansible roles or collections with Ansible in pull-based setup.

## Running

1. Install 3rd party coles and collections:
    ```
    sudo ansible-pull -U https://github.com/Arsenikki/ansible-pull-demo 00-pre-tasks.yaml
    ```
2. Run our actual playbook:
    ```
    sudo ansible-pull -U https://github.com/Arsenikki/ansible-pull-demo 01-docker.yaml
    ```
