# Custom my.cnf configuration for MySQL/MariaDB

This file is based on the Gist by Fotis (https://gist.github.com/fevangelou) which focuses on WHM/Cpanel environment.

Gist info: https://gist.github.com/fevangelou/0da9941e67a9c9bb2596

The trouble we had was that the settings contained in the Gist are not optimised for a custom server setup,
so with some trial an error we have created this mariadb_[your.serverhost].cnf file which you can use.

## Server Environment

- 8 Core / 30GB RAM
- Ubuntu 18/20
- NGiNX
- MariaDB
- HTTPD/Apache

## Location of my.cnf

Typically this is a custom file you create and is normally located at `/etc/mysql/conf.d/` 
You will need to create the a custom file example: `my.cnf` (We normally call this the host name of the server for easier reference)

## Testing and Feedback

If you would like to contribute different setups - open a pull request and follow the same format as the example file, so others may learn.

## Important

This file is not intended to be used out of the box. Always ensure you test and change values according to your environment.
