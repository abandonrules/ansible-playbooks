

install:
	ansible-playbook --connection=local \
	--extra-vars "inventory=127.0.0.1" \
	--inventory 127.0.0.1 \
	complete-desktop.yml

ssh:
	sudo apt install openssh-server 
	sudo systemctl enable ssh 
	sudo systemctl start ssh
