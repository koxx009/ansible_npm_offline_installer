NPM_offline_installer
=========

Requirements
------------

Place your .tgz node-packages in ./files

Role Variables
--------------

* `node-apps-dir`: path where will be placed NodeJS apps

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install node js environment
	  hosts: all
	  become: true
	  roles:
	    - yum_offline_installer
	    - nickjj.user
	    - npm_offline_installer
	  vars:
	    user_name: node
	    pack: node

License
-------

BSD

Author Information
------------------

TG: @Kolyunya_the_best
