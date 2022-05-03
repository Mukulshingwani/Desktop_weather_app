# Desktop_weather_app

## How to run
- Ensure Node.js is installed on your system, if not it can be installed from here [install](https://nodejs.org/en/)
- check if it has been installed properly by writing following into your command prompt :-
```bash
  node -v
  npm -v
```
- Install Electron using the following code 
```bash
npm i electron -g
``` 
- create a new electron app using the following code
``` bash
npx create-electron-app your-app-name
```
- If you want to run some different web app, make changes here
```bash
mainWindow.setTitle('title of the desktop app');
mainWindow.loadURL('http://www.yourwebpage.com');
```
- Run the created app by writing the following code
``` bash
npm start
```
