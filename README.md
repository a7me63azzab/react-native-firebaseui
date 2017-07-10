
# react-native-firebase-ui

## Getting started

`$ npm install react-native-firebase-ui --save`

### Mostly automatic installation

`$ react-native link react-native-firebase-ui`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-firebase-ui` and add `RNFirebaseUi.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNFirebaseUi.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import io.rumors.reactnativefirebaseui.RNFirebaseUiPackage;` to the imports at the top of the file
  - Add `new RNFirebaseUiPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-firebase-ui'
  	project(':react-native-firebase-ui').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-firebase-ui/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-firebase-ui')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNFirebaseUi.sln` in `node_modules/react-native-firebase-ui/windows/RNFirebaseUi.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNFirebaseUi;` to the usings at the top of the file
  - Add `new RNFirebaseUiPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNFirebaseUi from 'react-native-firebase-ui';

// TODO: What to do with the module?
RNFirebaseUi;
```
  