# Ansible-Playbooks
Ansible playbooks (mostly role) to install the most commonly software in your IT infrastructure

Roles are ways of automatically loading certain vars_files, tasks, and handlers based on a known file structure. Grouping content by roles also allows easy sharing of roles with other users.

Role Directory structure:

webservers.yml
fooservers.yml
roles/
    common/
        tasks/
        handlers/
        files/
        templates/
        vars/
        defaults/
        meta/
    webservers/
        tasks/
        defaults/
        meta/
        
        
You can create the role using the below command:

ansible-galaxy init role-1
