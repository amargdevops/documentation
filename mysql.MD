Developer has chosen the database MySQL. Hence, we are trying to install it up and configure it.

Versions of the DB Software you will get context from the developer, Meaning we need to check with developer.

# Install MySQL on Amazon Linux 2023

```bash
sudo dnf install mysql-server -y

#  Start MySQL Service
systemctl enable mysqld
systemctl start mysqld