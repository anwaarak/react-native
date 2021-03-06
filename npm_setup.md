## Setup project

> The create-react-native-app ("CRNA") CLI builds a project template based on Expo, 

`create-react-native-app my-project`

> By contrast, the react-native CLI's init command creates a plain React Native app template, with native iOS and Android projects you can modify

`npx react-native init AwesomeProject`


## React native vector icons

Guide : https://github.com/oblador/react-native-vector-icons#bundled-icon-sets

`npm install react-native-vector-icons --save`

`npm install react-native-elements --save`

`npm i redux-devtools-extension`

## Push Notifications

> https://github.com/zo0r/react-native-push-notification

`npm install --save react-native-push-notification`

## Navigation

> https://reactnavigation.org/docs/getting-started

`npm install @react-navigation/native --save`

`npm install react-native-screens react-native-safe-area-context --save`


> Stack Navigation 

`npm install @react-navigation/stack`

`npm install react-native-gesture-handler`

`npm install @react-native-masked-view/masked-view`



## React Devtools

`npm install -g react-devtools`

## Debugger

`https://reactnative.dev/docs/debugging`

`npm install react-native-debugger`

`npm install --save react-native-devsettings-android`

`npm install --save redux-devtools-extension`





If you want to enable debugging by default:

`import { NativeModules } from 'react-native';

if (__DEV__) {
  NativeModules.DevSettings.setIsDebuggingRemotely(true)
}`

To get this working on Android:

`npm install --save react-native-devsettings-android`

`react-native link react-native-devsettings-android`


## Logs

For IOS $ react-native log-ios
For Android $ react-native log-android

npx react-native log-ios
npx react-native log-android


https://medium.com/@tetsuyahasegawa/how-to-integrate-react-native-debugger-to-your-expo-react-native-project-db1d631fad02

