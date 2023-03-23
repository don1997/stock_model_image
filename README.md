Needed for the image portion for stock_model repo

This is contains the Docker file for the docker hub image used in the cloud.

# Google Cloud VM startup instructions

1. Start display Manager: `sudo service slim start`
2. Search `https://remotedesktop.google.com/access` for remote access. 

## Useful Commands
* `sudo docker images` Used to view a list of images on machine.
* `sudo docker ps` Used to view running docker procs.
* `sudo docker stop <proc id>` Used to stop proc enter id as param.
* `docker run -p <port #>:<port #> <name of your docker image>` Start docker image on local host.

* `sudo systemctl start docker` Start docker daemon
* `sudo systemctl stop docker` Stops docker daemon
