https://docs.ansible.com/ansible/latest/user_guide/playbooks_filters.html

https://docs.ansible.com/ansible/latest/user_guide/playbooks_templating.html

https://docs.ansible.com/ansible/latest/plugins/lookup/password.html

https://docs.ansible.com/ansible/latest/reference_appendices/special_variables.html

https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html

https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html?extIdCarryOver=true&sc_cid=701f2000001OH7EAAW

https://docs.ansible.com/ansible/latest/scenario_guides/vmware_scenarios/vmware_inventory_filters.html

ansible-doc -l ansible-playbooks --help

plugin for autom to very the syntex is linter-js-yaml https://docs.ansible.com/ansible/2.8/modules/modules_by_category.html https://docs.ansible.com/ansible/latest/user_guide/modules_intro.html https://docs.ansible.com/ansible/latest/collections/community/mysql/mysql_db_module.html#examples

ansible dev -m service -a "name=nginx state=stopped" ansible all -a 'hostname -s' -o ansible dev -m setup -a filter='ansible_distribution*' tail -5 /etc/shadow

ansible ubuntu -m setup -a 'gather_subset=network,!all,!min' 197 ansible ubuntu -m setup -a 'gather_subset=network,!all,!min' | wc -l 198 ansible ubuntu -m setup -a 'gather_subset=network' | wc -l 199 ansible ubuntu -m setup -a 'filter=ansible_memfree_mb' | wc -l 200 ansible ubuntu -m setup -a 'filter=ansible_memfree_mb' 201 ansible ubuntu -m setup -a 'filter=ansible*' 202 ansible ubuntu -m setup -a 'filter=ansible_memfree*' 203 ansible ubuntu -m setup -a 'filter=ansible_mem*'

ansible ubuntu -m setup | more
