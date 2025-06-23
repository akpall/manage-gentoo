files/ssh/manage-gentoo files/ssh/manage-gentoo.pub:
	ssh-keygen -f files/ssh/manage-gentoo -C "manage-gentoo" -N "" && \
	  ansible-vault encrypt files/ssh/manage-gentoo

generate-ssh-keys: files/ssh/manage-gentoo files/ssh/manage-gentoo.pub
