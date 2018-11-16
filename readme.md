
# thanks pingcap/tidb-ansible and the download server. 

# prepare 
1. centos 7.x
2. ansible version > 2.4.x
3. deploy by root
4. nonessh by root

#deply steps
1. ansible-playbook local_prepare.yml
2. ansible-playbook bootstrap.yml
3. ansible-playbook deploy.yml
4. ansible-playbook start.yml
5. ansible-playbook stop.yml
