# heroku_git

## Deploy the app

The app is already ready to be deployed.
You have to login to your Heroku account and create an app, just give it a name that we will refer to with [appname] and that's it, just click on "Create app".
Then, you have to login on Heroku using the CLI with `heroku login`, start a git repository using `git init`.
Furthermore, with `heroku git:remote -a [appname]` you are going to create a heroku repo based on your git repository.
Add the changes you did to your git with `git add .` in order to be able to commit with `git commit -am "First python app"`
Finally, push the changes with `git push heroku master` and your application should be able to run at the address : https://[appname].herokuapp.com
