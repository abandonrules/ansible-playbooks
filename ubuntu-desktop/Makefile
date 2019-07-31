

install:
	ansible-playbook --connection=local \
	--extra-vars "inventory=127.0.0.1" \
	--inventory 127.0.0.1 \
	complete-desktop.yml

ssh:
	sudo apt install openssh-server;systemctl enable ssh && systemctl start ssh
