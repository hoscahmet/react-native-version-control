
## Installation

### Step 1

Using npm:
```bash
npm install --save react-native-device-info
```

or using yarn:

```bash 
yarn add react-native-device-info
```
### Linking (for React Native <= 0.59 only, React Native >= 0.60 skip this as auto-linking should work)
### Automatic
```bash 
react-native link react-native-device-info
```
(or using rnpm for versions of React Native < 0.27)

```bash 
rnpm link react-native-device-info
```
For iOS users using Pods You still need to run pod install after running the above link command inside your IOS folder.

[Help](https://github.com/react-native-community/react-native-device-info) for install react-native-device-info.
### Step 2

```bash 
npm install react-native-update-control
```

## Usage

```javaScript

import VersionControl from 'react-native-update-control';

    VersionControl({
    title:"App Update Title", 
    description:"App Update Description",
    cancelText:"CANCEL",
    okText:"UPDATE"
    });
```

