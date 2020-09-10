# README

This is a sample React + Rails Todo list app. To run this:

```
rails db:migrate

cd todo-app && npm install

heroku local -f Procfile.dev
```

To run on Heroku:

``` 
heroku run rake db:migrate db:seed --app HEROKU_APP
