
# react-native-letter

## Getting started

`$ npm install react-native-letter --save`

### Mostly automatic installation

`$ react-native link react-native-letter`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-letter` and add `RNLetter.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNLetter.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.categroy.letter.lib.RNLetterPackage;` to the imports at the top of the file
  - Add `new RNLetterPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-letter'
  	project(':react-native-letter').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-letter/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-letter')
  	```


## Usage
```javascript
import RNLetter from 'react-native-letter';

// TODO: What to do with the module?
RNLetter;
```
  