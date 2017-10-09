![](/heroku-logo.jpg)
#A PHP Web🚪Hosting on Heroku
- Download Heroku Toolbelt ~ an Account with heroku ~ Heroku login with CMD
- Run `heroku` from CLI 
- ![](/heroku.png)
- Clone the files to your local machine `git clone https://github.com/BlackrockDigital/startbootstrap-freelancer.git`
- ![](/heroku1.png)
- Run `heroku create` to create an app
- ![](/heroku2.png)
- Goto the checkout folder and create a PHP file named `index.php`, pointing to /index.html` or /home.html
```
<?php include_once("index.html");?>
```
- Run the below git commands to commit the code to the repository of your app
```
git init .
git add .
git commit -m "MyNewCommit"
heroku git:remote -a <app>
git push heroku master
```
- You can scale the application to one web server `heroku ps:scale web=1`
- Type the command `heroku open` to open the application in the browser
- Check in browser with the URL: `https://<the name of the app>.herokuapp.com`
