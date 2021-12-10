# heroku_git

## Deploy the app

The app itself is already ready to be deployed. </br>
You have to login to your Heroku account and create an app, just give it a name that we will refer to with [appname] and that's it, just click on "Create app". </br>
You can check your Heroku apps using `heroku apps`
Then, you have to login on Heroku using the CLI with `heroku login`, start a git repository using `git init`. </br>
Furthermore, with `heroku git:remote -a [appname]` you are going to create a heroku repo based on your git repository. </br>
Add the changes you did to your git with `git add .` in order to be able to commit with `git commit -am "First python app"` </br>
Finally, push the changes with `git push heroku master` and your application should be able to run at the address : https://[appname].herokuapp.com
