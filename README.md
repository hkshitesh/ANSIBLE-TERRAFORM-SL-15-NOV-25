## Ansible cmd command for variable

ansible-playbook -i hosts.ini package_manage.yml -e "packages=git,htop" -e "operation=install"
