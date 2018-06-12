# What does script do

  - pull changes from remote
  - make release builds from source code of java and js
  - shut down old docker containers
  - create new docker images
  - start new docker containers

# Before start

  - Check that you downloaded git projects mail-server and mail-web
  - Check that git vesrion is 2.+
  - Check that you run 'release' script is under sudo user
  - Check in 'release' script variables: NPM_USER, BRANCH, DIR_MAIL_SERVER, DIR_MAIL_WEB
  
| Variable | Description |
| ------ | ------ |
| NPM_USER | under what user will the npm assembly be rendered |
| BRANCH | from what branch will release be provided |
| DIR_MAIL_SERVER | directory of mail-server project with source code and git file |
| DIR_MAIL_WEB | directory of mail-web project with source code and git file |
  

# START
```sh
./release
```

That's all! Release was done!