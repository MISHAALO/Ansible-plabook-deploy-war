cp -r inventories/* /etc/ansible/ \n
cp -r roles/* /etc/ansible/roles \n
sudo ansible-playbook soop-deploy-war.yml -e "sprint_version=1234" 