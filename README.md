# autoupdate-ansible

Auto updater for all servers and VM's using Ansible.

Currently only supports Debian based servers, as I don't not use other distributions yet.

Copy the "sample-host.ini" file to /inventory/ as "hosts.ini" as well copy the "ansible.example.cfg" to the root directory of this repository and rename is "ansible.cfg".

If you are changing the directory of the "hosts.ini" file, be sure to update it in the "ansible.cfg" file.

You can use the "autoupdate.sh" script to run the updater as a cronjob.

Feel free to make improvements and changes as you see fit, share it with me if you do, this is a very basic script only for my use case of keeping my servers auto updated.
