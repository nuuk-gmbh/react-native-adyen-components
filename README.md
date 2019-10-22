# react-native-adyen-components
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

## Getting started

`$ npm install react-native-adyen-components --save`

### Mostly automatic installation

`$ react-native link react-native-adyen-components`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-adyen-components` and add `AdyenComponents.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libAdyenComponents.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.AdyenComponentsPackage;` to the imports at the top of the file
  - Add `new AdyenComponentsPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-adyen-components'
  	project(':react-native-adyen-components').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-adyen-components/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-adyen-components')
  	```


## Usage
```javascript
import AdyenComponents from 'react-native-adyen-components';

// TODO: What to do with the module?
AdyenComponents;
```

## Sponsoring

Thanks to Neolotto / [Golotto](https://www.golotto.de/) for sponsoring this development.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/bonesyblue"><img src="https://avatars0.githubusercontent.com/u/7486722?v=4" width="100px;" alt="Jonathan Bones"/><br /><sub><b>Jonathan Bones</b></sub></a><br /><a href="https://github.com/nuuk-gmbh/react-native-adyen-components/commits?author=bonesyblue" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!