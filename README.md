# Credit

All credit goes to Miroslav Prasil (https://hub.docker.com/r/mprasil/dokuwiki/). However, there was an error in his (her?) repository on bitbucket but either 1) I don't know how to work bitbucket, or 2) the repo is locked down so I could not submit a pull request or an issue ticket.

So, I have copied the repo here so that I can make one simple correction.

# DokuWiki docker container

## To run image:

`docker run -d -p 8888:80 --name dokuwiki pconwell/docuwiki`

Once the container is installed, you can set up the wiki by going to http://127.0.0.1:8888/install.php in your browser (if installed on the local machine) or http://your.ip.here:8888/install.php if installed on a remote machine.

# Notes

I accidentally created this repo with `docuwiki` instaed of `dokuwiki` (notice `c` instead of `k` in `dokuwiki`). This was a typo on my part.
