Update - original author seems to have finally updated his docker container. This repo is no longer needed.

## Credit

All credit goes to Miroslav Prasil (https://hub.docker.com/r/mprasil/dokuwiki/). However, there is an error in that repo and the author (apparently) does not accept pull requests or issues so I have forked the repo here to correct the error.

## DokuWiki docker container

### To run image:

`docker run -d -p 8888:80 --name dokuwiki pconwell/dokuwiki`

It is a fairly small container, so it should only take a few minutes to install.

Once the container is installed, you can set up the wiki by going to http://127.0.0.1:8888/install.php in your browser (if installed on the local machine) or http://your.ip.here:8888/install.php if installed on a remote machine. The setup is very basic and should only take a minute or two.
