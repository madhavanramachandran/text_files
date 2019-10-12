Assuming, we have running instance of nginx in our system.

###Commands

####Check nginx status
* `nginx -v` : to check the version of the nginx server installed.
* `pd -ef | grep nginx` : Check the running process of nginx
* `nginx -V` : nginx version + build information + configuration arguments
* `nginx -t` (or) `nginx -T`: validate nginx configuration
* `nginx -s <signal` : `stop`, `quit`, `reload`, `reopen`
* `curl localhost` : return the index.html of nginx folder. 

###To Learn:
* apt package management system
* GPG package signing key 
* `ps` command - running process in system