# Ansible-Playbooks
Ansible playbooks (mostly role) to install the most commonly software in your IT infrastructure

Roles are ways of automatically loading certain vars_files, tasks, and handlers based on a known file structure. Grouping content by roles also allows easy sharing of roles with other users.

Role Directory structure:

.travis.yml

README.md

defaults/

    main.yml
    
files/

handlers/

    main.yml
    
meta/

    main.yml
    
tasks/

    main.yml
    
templates/

tests/

    inventory
    
    test.yml
    
vars/

    main.yml
        
        
You can create the role using the below command:

ansible-galaxy init test-role
