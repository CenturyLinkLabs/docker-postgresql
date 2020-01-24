## NOTE

This repo is no longer being maintained. Users are welcome to fork it, but we make no warranty of its functionality.

CenturyLink postgresql
=================
[![](https://badge.imagelayers.io/centurylink/postgresql.svg)](https://imagelayers.io/?images=centurylink/postgresql:latest 'Get your own badge on imagelayers.io')

This image borrows heavily from [paintedfox/postgresql](https://registry.hub.docker.com/u/paintedfox/postgresql/). This image was created, however, to lock in the versions of the base image and postgresql to ensure it works in conjunction with other images and templates created with [Panamax](http://panamax.io).

Use the following environmental variables to create your database:

`DB` = Database name

`USER` = Database username

`PASS` = User's password

Example usage:
`docker run --name postgresql -e "DB=database1" -e "PASS=password" -e "USER=user1" centurylink/postgresql`

