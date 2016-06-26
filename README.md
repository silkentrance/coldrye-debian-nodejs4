# coldrye-debian-nodejs

[![coldrye/debian-nodejs](http://dockeri.co/image/coldrye/debian-nodejs)](https://hub.docker.com/r/coldrye/debian-nodejs/)


## Description

Packages various node versions from deb.nodesource.com for various debian releases based on coldrye/debian-tini.


## Image Releases

Images are released for the following debian releases.

- jessie
- testing (stretch)

See https://hub.docker.com/r/coldrye/debian-nodejs/tags/ for a complete list.


## Notes

- /usr/bin/nodejs is symlinked to /usr/bin/node
- npm is updated to the lastest version
- no additional NPM packages have been installed
- no start command is set, derived images must define their own start command which will then be run by tini

