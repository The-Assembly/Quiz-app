# Quiz-app
## PART 0 - Installing dependencies 

<b/ >WINDOWS USER: <b> <br/>
a. Open an Administrator Command Prompt (right click Command Prompt and select "Run as Administrator"), then run the following command: <br/>

```choco install -y nodejs.install python2 jdk8``` 

b. Install the React Native command line interface: <br/>

```npm install -g react-native-cli```

<b/>MAC OS USERS:  <b>

a. Run the following commands in a Terminal after installing Homebrew: <br/>

```brew install node```
```brew install watchman```

b. Install the React Native command line interface: <br/>

```npm install -g react-native-cli```

## PART 1 - Creating the Quiz App 
Assuming that Node is installed, you can use npm to install the create-react-native-app command line utility: <br/>

Step 1: ```npm install -g create-react-native-app``` <br/>

Step 2: ```npm install -g npm@4.6.1``` <br/>

Then run the following commands to create a new React Native project called "QuizApp": 

Step 3:``` create-react-native-app QuizApp``` <br/> 
(should take some time) <br/>

Step 4: transfer the github files, scr folder and the App.js to your "QuizApp" directory. <br/>

Step 5:Next on the command prompt type: <br/>

 ```cd QuizApp``` 

Step 6: Install two node modules <br/>

```npm install --save react-native-router-flux react-native-elements```

# PART 2 - Running your React Native application

Install the Expo client app on your iOS or Android phone and connect to the same wireless network as your computer. Using the Expo app, scan the QR code from your terminal to open your project. <br/>

Step 7: ```npm start``` 
