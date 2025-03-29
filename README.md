#ad-hoc commands
ansible -i ineventory all -m "shell" -a "whatever you want to do"
# to run a playbook
ansible-playbook -i inventory ansibleplaybook.yaml
