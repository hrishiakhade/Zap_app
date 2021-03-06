# Zap_app  
         A react-native app which stores User's Registration details on Hasura cluster DB and Google Spreadsheet and 
     notifies user along with the Google Spreadsheet link where Details are stored using Zapier Service.Backend is   
     done using Python-Flask.
## Preview  

![Alt Text](https://i.imgflip.com/23tmt4.gif)
![Alt Text](https://i.imgflip.com/23tn9u.gif) 

## Google Drive APK Link 
   Download app-release.apk from here https://drive.google.com/open?id=1emaK5FMiH8Pq50oYpgabYBRN6xJW7yhi
    
This project was created by `react-native-init` command.
    
## Dependencies
  * [React Native](https://facebook.github.io/react-native/)
  * [NativeBase for UI Elements](https://github.com/GeekyAnts/NativeBase)
  * [React Native Datepicker](https://github.com/xgfe/react-native-datepicker)
 
 ## Pre-Requisites
  * [Node](https://nodejs.org/) 4.x or better  
  * [React Native](http://facebook.github.io/react-native/docs/getting-started.html) for development 
  * [Android SDK](http://facebook.github.io/react-native/docs/getting-started.html) for Android development (optional) 
  * [Android Lollipop](https://www.android.com/versions/lollipop-5-0/) or better for Android device testing (optional) 
  * [Hasura cli](https://docs.hasura.io/0.15/manual/install-hasura-cli.html)
  
 ## Getting Started 
  #### 1. Open Command Prompt or gitbash and install these commands   
      >> npm install -g npm@4.6.1
      >> npm install -g yarn@1.3.2
      >> npm install -g react-native-cli@2.0.1
      
   #### 2. Project Installation Procedure
       >> git clone https://github.com/hrishiakhade/Zap_app.git
       >> cd Zap_app
       >> cd Zapier
       >> npm install  
       >> npm install native-base --save
       >> npm install react-native-datepicker --save
       >> react-native link
  
  #### 3. Post data to your own Hasura cluster (optional)
         >> open Zap.js 
         >> Replace CLUSTER_NAME with your own hasura cluster from 
            const DBUrl ="https://app.CLUSTER_NAME.hasura-app.io/signup" .
  ## Running
   ####  Run app in Android device(enable USB Debugging First) or emulator   
         'react-native run-android'
         
   ####  Run app in iOS device(enable USB Debugging First) or emulator
         'react-native run-ios' 
         
   ####  Generate Signed APK 
         Android requires that all apps be digitally signed with a certificate before they can be installed, so to 
    distribute your Android application via Google Play store, you'll need to generate a signed release APK.
   Follow the instructions here https://facebook.github.io/react-native/docs/signed-apk-android.html to generate Signed APK .
   
  

  

 

