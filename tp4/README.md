ansible-galaxy install -r formation-ansible/tp4/requirements.yml

ansible-playbook -i formation-ansible/tp4/hosts.yml formation-ansible/tp4/remove_packages.yml

ansible-playbook -i formation-ansible/tp4/hosts.yml formation-ansible/tp4/tp4.yml
