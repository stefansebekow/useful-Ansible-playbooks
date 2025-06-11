# useful-Ansible-playbooks
Collection of useful ansible playbooks

+ updateupgrade.yml

In this Ansible task, I automatically perform updates and pending upgrades in my home lab. A variable is then populated to check whether a reboot is necessary in the event of a kernel update or outdated libraries. Depending on whether the reboot is a hypervisor or the guest machines running on it, the reboot is scheduled at a different time.

+ secure_sshd_conf.yml

Force only ssh key access and no root login for sshd conf on all nodes
