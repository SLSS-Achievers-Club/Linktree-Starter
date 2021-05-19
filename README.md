# LinkTree Clone ran by SLSS-AchieversClub

## Getting Started
To install Node Modules:
```
npm install
```
To run the application:
```
npm start
```

------------------------------------------
## Hosting
You first need to install firebase tools to do this you need to type:
```
npm install firebase-tools -g
```
This basically installs firebase tools globaly on your PC.

Next you have to create a project with firebase so head over to this [link](https://accounts.google.com/signin/v2/identifier?passive=1209600&osid=1&continue=https%3A%2F%2Fconsole.firebase.google.com%2F&followup=https%3A%2F%2Fconsole.firebase.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin)
and login after doing so go to this [link](https://console.firebase.google.com/u/0/?pli=1) and click add project. You can name your project whatever you want, enable google analytics and choose your defualt account for firebase and continue. After that your good to go to the next part.

Last but not least you have to setup firebase within your source code to do so initialize firebase in your app's folder you can do this by typing:
```
firebase init
```
Navigate down to hosting than click using an existing project and click the name of the project that you created earlier. For your public directory you need to choose your build folder to make your website more optimized and you want to configure your website as a single-page app. 

After finishing you firebase initialization you can type the last two commands
```
npm run build
```
than 
```
firebase deploy
```
