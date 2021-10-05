# Deployment using Heroku and MongoDB

commands in the terminal

```zsh
heroku apps:create mypurplefoodapp
 
 7457* heroku config:set DB_URL="mongodb+srv://rbell9:7uEzwFWIBUEFaCNs@myappdb.h0itf.mongodb.net/myFirstDatabase?retryWrites=true&w=majority&useNewUrlParser=true&useUnifiedTopology=true"
 
 7458* heroku config:set JWT_SECRET=thisismytoken
 
 7459* git remote -v
 
 7460* git push heroku main
 
 7461* git status
```

## Scenarios

- [ ] Seed database

## `MongoDB`

