# deploy
deployment scripts used for self-hosting and etc...

## setup
if you came from the backend repo, here's how to get quickly started:
```sh
git clone https://github.com/badmsgchat/deploy badmsg && cd badmsg
sh deploy init # initiates the repo
sh deploy dev # starts the server
```
you can also use `wget https://raw.githubusercontent.com/badmsgchat/deploy/main/deploy` to get the script.

### usage
from the cli:
```
usage: deploy <command>
  dev/start - starts the server

  init - initiates and sets everything up (one time use)
  build - builds everything (ran automatically by the dev command)
```
