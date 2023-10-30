[Description of This repo]

-master and slave
-lamp stack
-laravel
-ansible


[sections explanation]

Ansible-playbook:

-ansible.cfg (file)
-inventory
-site.yaml


-files:
	-laravel-slave.sh


-master-slave file:

	-launches the master and slave virtual machines

-laravel.sh:

	-deploy laravel on the master

[running the repository]

- .env:

changed USERNAME, DATABASE, PASSWORD

- mysql

(loading the script) ./laravel.sh emmanuel1 eon30

- ansible config file

(changed the severname to my ip address)




