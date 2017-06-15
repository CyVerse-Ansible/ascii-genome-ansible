# ascii-genome-ansible

Installs [ASCIIGenome Browser](https://github.com/dariober/ASCIIGenome)

[![Build Status](https://travis-ci.org/CyVerse-Ansible/ascii-genome-ansible.svg?branch=master)](https://travis-ci.org/CyVerse-Ansible/ascii-genome-ansible)

### Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

| Variable                | Required | Default | Choices                   | Comments                                   |
|-------------------------|----------|---------|---------------------------|--------------------------------------------|
| VERSION                 | yes      | 1.7.0   | Any version number        | Controls the version of installed software |
| JAVA                    | yes      |         | ANy java 1.7+ package     | Name of the java package to install        |
