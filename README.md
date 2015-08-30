This is an [Ansible 2.0](http://ansible.com) playbook to bootstrap a deploy digital ocean droplet with ansible service.

# env setup
Ansible 2.0 or higher is required for this playbook.

# run
```
ansible-playbook -i localhost --extra-vars '{"API_TOKEN":"xxx"}' deploy_ss_droplet.yml
```