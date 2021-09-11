# HyperShell Docker Host Wordpress container set
This container implements a set of tools suitable for Wordpress site hosting, monitoring and management:
- Wordpress
- MySQL 5.7
- HyperShell Docker management container (Hysh)
- PHPMyAdmin
- LinuxServer SWAG

## Starting with **docker-compose**

**IMPORTANT** - you must have your DNS A-record set up!

Edit `.env` file and replace provided dummy Chaincode ID, Email and URL

```shell
CHAINCODE_ID_NAME=54acec8c9aa84185876e72256d039e32
EMAIL=
URL=
```
with your real device Chaincode ID, your email and your site url (for SSL Cert).

Simply execute:

```shell
docker-compose up -d
```
