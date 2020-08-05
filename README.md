# Ansible-Playbooks
Write Once Use Many(Reusable) Ansible roles to install some of the commonly software/packages in your IT infrastructure

Roles are ways of automatically loading certain vars_files, tasks, and handlers based on a known file structure. Grouping content by roles also allows easy sharing of roles with other users.

Role Directory structure:

rolename/

    .travis.yml
    
    README.md
    
    defaults/
    
    files/
    
    handlers/
    
    meta/
    
    tasks/
    
    templates/
    
    tests/
    
    vars/
        
        
You can create the role using the below command:

ansible-galaxy init test-role
