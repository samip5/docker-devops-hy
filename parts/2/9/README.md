# Docker Toolbox for Windows - Issues

Peristent data with postgres and Windows will face a permissions issue 
due to the SAMBA/CIFS share between the actual docker vm and Windows 
host. There are multiple issues on the forums regarding it.

https://forums.docker.com/t/data-directory-var-lib-postgresql-data-pgdata-has-wrong-ownership/17963/27
