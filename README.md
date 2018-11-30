# recon-moloch

This role will deploy Elasticsearch and Moloch to a single system, currently only tested on Ubuntu 16.04.

* Modify Elasticsearch variables in playbook.yml and roles/elasticsearch/defaults/main.yml
* Modify Moloch variables in playbook.yml 
* Run the following

```
ansible-playbook playbook.yml
```
