cp -r inventories/* /etc/ansible/

cp -r roles/* /etc/ansible/roles 

sudo ansible-playbook soop-deploy-war.yml -e "sprint_version=1234" 