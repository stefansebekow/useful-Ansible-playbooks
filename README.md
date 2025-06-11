# useful-Ansible-playbooks
Collection of useful ansible playbooks

+ updateupgrade.yml

In this Ansible task, I automatically perform updates and pending upgrades in my home lab. A variable is then populated to check whether a reboot is necessary in the event of a kernel update or outdated libraries. Depending on whether the reboot is a hypervisor or the guest machines running on it, the reboot is scheduled at a different time.

+ force_sshd_conf.yml

Another, clearer example of the basic idea behind Ansible is the following task, which allows us to periodically overwrite configuration discrepancies in the SSHD config. It may be that I need to switch to password-based login at some point and change the config, or a future upgrade of the SSHD config discards the previous changes. It may even be that I forget to undo the change. Whatever happens!
