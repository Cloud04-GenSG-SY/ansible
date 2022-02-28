To run playbooks

1. Download the appropriate challenge folder
2. Download inventory-file
3. Run "ansible-playbook [filepath of playbook]" OR
   "ansible-playbook -K [filepath of playbook]" if the playbook needs elevated permission

To delete whatever the playbook did

1. Run "ansible-playbook [filepath of playbook] --tags setup"

