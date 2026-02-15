# LEMP-stack deploying

Manually deploying LEMP-stack blog PHP web-application (https://github.com/m1k1o/blog) on Debian-based Linux with Ansible

## Roles

- "git-clone" role: clones repository, changes file and directory permissions and copies config.ini
- "php" role: installes and enables PHP 7.4
- "mariadb" role: installes and enables MariaDB 10.11, creates database, blog user and restores DB
- "nginx" role: provides nginx with configuration file

## Tests

The playbook was tested on Ubuntu 24.04 and Debian 12