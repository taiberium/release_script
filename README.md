# Before start

  - Check that git vesrion is 2.+
  - Check that you run 'release' script is under sudo user
  - Check in 'release' script variables: NPM_USER, BRANCH, DIR_MAIL_SERVER, DIR_MAIL_WEB
  
| Variable | Description |
| ------ | ------ |
| NPM_USER | is under what user will the npm assembly be rendered |
| BRANCH | is from what branch will release be provided |
| DIR_MAIL_SERVER | direcotory of mail-server project with source code and git file |
| DIR_MAIL_WEB | direcotory of mail-web project with source code and git file |
  

# START
```sh
./release
```

That's all! Release was done!