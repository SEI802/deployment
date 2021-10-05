# Deployment using Heroku and MongoDB

commands in the terminal

```zsh
heroku apps:create mypurplefoodapp
 
heroku config:set DB_URL="mongodb+srv://rbell9:7uEzwFWIBUEFaCNs@myappdb.h0itf.mongodb.net/myFirstDatabase?retryWrites=true&w=majority&useNewUrlParser=true&useUnifiedTopology=true"
 
heroku config:set JWT_SECRET=thisismytoken
 
git remote -v

git push heroku main
 
git status
```

## Scenarios

- [ ] Seed database

## `MongoDB`

