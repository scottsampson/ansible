* for all hosts as defined in /etc/ansible/hosts
    ansible all -a "/bin/echo hello"

* for groups as defined in /etc/ansible/hosts []
    ansible cloudspace -a "/bin/echo hello"
