:construction: ***DEVELOPING*** :construction:

# **template-ansible-collection**

![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=flat&logo=ansible&logoColor=white)
![License](https://badgen.net/github/license/ironwolphern/template-ansible-collection)
![Release](https://badgen.net/github/release/ironwolphern/template-ansible-collection)
![PRs](https://badgen.net/github/prs/ironwolphern/template-ansible-collection)
![Issues](https://badgen.net/github/issues/ironwolphern/template-ansible-collection)
[![Ansible Lint](https://github.com/ironwolphern/template-ansible-collection/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/ironwolphern/template-ansible-collection/actions/workflows/ansible-lint.yml)
![Dependabot](https://badgen.net/github/dependabot/ironwolphern/template-ansible-collection)

A brief description of the collection goes here.

## *Requirements*

Any pre-requisites that may not be covered by Ansible itself or the collection should be mentioned here. For instance, if the collection uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## *Collection Variables*

A description of the settable variables for this collection should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the collection. Any variables that are read from other collections and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

This is a list of required and optinal variables and parameters for this collection:

| **Parameter**                  | **Description**            | **Type** |     **Default**     |**Required**|
|--------------------------------|----------------------------|----------|:-------------------:|:----------:|
| variable_input        | description             |  type  | default value          |     yes/no     |

## *Dependencies*

A list of other collections hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other collections, or variables that are used from other collections.

## *Example Playbook*

This is an example of use collection with optionals and required parameters:

*playbook-file.yml*
```yaml
    - hosts: example
      collections:
        - example-collection
      vars:
        var_input_1: XXXXXXXX
        var_input_2: 00000000
```

These are some examples of the use of this playbook with the different tags that can be used in this collection:

Install and configure for example
```bash
  ansible-playbook -i inventory playbook-file.yml
```
## *License*

MIT

## *Author Information*

This collection was created in 2023 by:

- Fernando Hernández San Felipe (ironwolphern@outlook.com)
