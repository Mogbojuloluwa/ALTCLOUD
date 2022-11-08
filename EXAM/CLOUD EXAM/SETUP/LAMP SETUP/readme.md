This playbook will install a LAMP environment (Linux, Apache, mySQL and PHP) on an Ubuntu 20 virtual machine

variables explained

- `mysql_root_password`: the password for the MySQL root account.
- `app_user`: a remote non-root user on the Ansible host that will own the application files.
- `http_host`: your domain name.
- `http_conf`: the name of the configuration file that will be created within Apache.
- `http_port`: HTTP port, default is 80.
- 

