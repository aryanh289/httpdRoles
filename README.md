Role Name
=========

Role name is 'http'. This is a very basic test level ansible-role created specifically for testing purpose and learning how actually the ansible roles work.

Requirements
------------

Just few prerequisites:
1. You must have python3 installed
2. You should have ansible installed and that's it.
3. Use this role with any other ansible playbook easily.

Role Variables
--------------

Just one:
`dest` contains the destination of the directory path where i have to copy my index.html. But you can keep more, like filename or service name.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - httpd (my_role_name_is_httpd, so you just have to put the rolename along with the path, until or unless your playbook and my role are in the same dir)

License
-------

BSD

Author Information
------------------

I am Harsh Aryan. I love automation. ;-)
