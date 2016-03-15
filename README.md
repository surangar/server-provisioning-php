# server-provisioning-php
server provisioning with php


Instructions to execute it

Clone a content of repo or download a zip file to the relevant ansible installed server.
If you download a zip file unzip it and go inside of the folder (server-provisioning-php-master).
Then open the "hosts" file and add IP address of the relevant server.
Then edit "ansible_ssh_user=" field with relevant username.
After editing the host file please check the connectivity using "ansible php -m ping" command.
Then execute server provisioning script using "ansible-playbook provosioning.yml --ask-sudo-pass" command.
After the ansible script completes open the host file of your PC and add "<Relavant-IP-Address>   phpinfo.ssr.com" to it.
Then put "phpinfo.ssr.com" on a web browser and check whether php info page is loading.
