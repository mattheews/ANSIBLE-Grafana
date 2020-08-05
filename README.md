TODO:

1. ADD FUNCTIONALITY FOR TELEGRAF TO MANIPULATE RESTART TASK IF PREVIOUS TASKS ARE EXECUTGED
2. MOVE UP VARIABLES FROM ROLES VARS FILES INTO GROUP / HOSTS VRAS
3. DEBUG WHY I CAN'T USE KEY:VALUE VARIABLE IN PLAYBOOKS: https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html
4. CHANGE INSTALLATION METHOD OF PIP TO VARIABLES
5. DEBUG WHY I CAN'T INSTALL PIP:
TASK [../roles/influxdb : Install Python pip] *********************************************************************************************************
fatal: [192.168.2.3]: FAILED! => {"ansible_facts": {"pkg_mgr": "yum"}, "changed": false, "msg": "The Python 2 bindings for rpm are needed for this module. If you require Python 3 support use the `dnf` Ansible module instead.. The Python 2 yum module is needed for this module. If you require Python 3 support use the `dnf` Ansible module instead."}

