cm_ansible 
---------

**create / delete a Cloudera cluster**

This is an Ansible module that allows to create and delete a Cloudera cluster.

### Prerequisites
- `cm-api` module to interact with Cloudera Manager: https://cloudera.github.io/cm_api


### How to use it

Being a custom Ansible module, it can be used in a couple of different ways:

* put the file in a library folder under the structure of your cookbook (like in this example playbook)
* have ANSIBLE_LIBRARY environment variable to point to the folder where the module resides

### Example run:

- Customize the cluster settings via the `cloudera.yml` file.

- Run:
  ```
  ansible-playbook -i inventory/localhost cloudera.yml
  ```
