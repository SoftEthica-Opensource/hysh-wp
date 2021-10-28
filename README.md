# HyperShell Docker Host WordPress container set
This build implements a set of tools suitable for WordPress site hosting, monitoring and management:
- WordPress
- MySQL 5.7
- WordPress CLI
- HyperShell Docker management container (Hysh)
- PHPMyAdmin
- LinuxServer SWAG

## Starting with **docker-compose**

**IMPORTANT** - you must have your DNS A-record set up!

1. Edit `.env` file and replace provided dummy Chaincode ID, Email, URL and DB creds

```shell
CHAINCODE_ID_NAME=54acec8c9aa84185876e72256d039e32
EMAIL=
URL=
...
MYSQL_HOST=db
MYSQL_USER=exampleuser
MYSQL_PASSWORD=examplepass
MYSQL_NAME=exampledb
```
with your real device Chaincode ID, DB creds, your email and your site url (for SSL Cert).

2. Simply execute:

```shell
docker-compose up -d
```
