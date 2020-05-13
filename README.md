# react-native-dateinput
React Native TextInput for dates and birthdays

<a href="https://www.npmjs.org/package/react-native-dateinput">
  <img src="https://badge.fury.io/js/react-native-dateinput.svg" alt="NPM package version." />
</a>
<a href="https://github.com/react-native-community/react-native-dateinput">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT license." />
</a>

## Examples

<img src="https://react-native-dateinput.s3-us-west-1.amazonaws.com/react-native-dateinput.ios.gif" width="300" alt="React Native Date TextInput on iOS" />

<img src="https://react-native-dateinput.s3-us-west-1.amazonaws.com/react-native-dateinput.android.gif" width="300" alt="React Native Date TextInput on Android" />

## Setup

```bash
npm install --save react-native-dateinput

# --- or ---

yarn add react-native-dateinput
```

## Usage

```javascript
import DateInput from 'react-native-dateinput';
...
<DateInput
    mask={'DD/MM/YYYY'}
    onChange={date => console.log(date)}
    validate={false} // true by default
    activeColor={'red'} // #7368FF by default
/>
...
```