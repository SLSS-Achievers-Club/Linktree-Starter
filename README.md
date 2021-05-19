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
1) You first need to install firebase tools:
    ```
    npm install firebase-tools -g
    ```

2) Now you need to create a project with firebase. Click this [link](https://accounts.google.com/signin/v2/identifier?passive=1209600&osid=1&continue=https%3A%2F%2Fconsole.firebase.google.com%2F&followup=https%3A%2F%2Fconsole.firebase.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin)
and login 
3) Now click this [link](https://console.firebase.google.com/u/0/?pli=1) and select "create a project". You can name your project whatever you want. Be sure to enable google analytics and choose your default account for firebase and continue.
4) Login to Firebase on your console. This will open up a new window to login with the account you used to create the project:
    ```
    firebase login
    ```
5) To setup firebase within your source code:
    ```
    firebase init
    ```
6) Navigate down to hosting on Firebase than click using an existing project and click the name of the project that you created earlier. For your public directory you need to choose your build folder to make your website more optimized and you want to configure your website as a single-page app. 

7) Now type the  following commands to finish the hosting setup: 
    ```
    npm run build
    ```
    ```
    firebase deploy
    ```
