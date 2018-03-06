# Ansible Playbooks

Several ansible playbooks used for different projects.

## Prerequisites

It is necessary to have installed Ansible. Here are the [instructions](http://docs.ansible.com/ansible/latest/intro_installation.html) to install Ansible.

## How to execute them

Here are a few instructions on how to execute the different playbooks. To check the execution and see the differences, we can use the following command:

```
ansible-playbook name_of_playbook -C -D
```

To execute just a tag or various tags, we can use:

```
ansible-playbook name_of_playbook -t tag
```

To execute the whole playbook:

```
ansible-playbook name_of_playbook
```