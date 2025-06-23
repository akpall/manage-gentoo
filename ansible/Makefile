playbook:
	ansible-playbook playbook.yaml
.PHONY: playbook

files/ssh/manage-gentoo files/ssh/manage-gentoo.pub:
	ssh-keygen -f files/ssh/manage-gentoo -C "manage-gentoo" -N ""

generate-ssh-keys: files/ssh/manage-gentoo files/ssh/manage-gentoo.pub
.PHONY: generate-ssh-keys
