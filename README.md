# react-native-date-input
React Native TextInput for dates and birthdays

<a href="https://www.npmjs.org/package/@maksymblank/react-native-date-input">
  <img src="https://badge.fury.io/js/%40maksymblank%2Freact-native-date-input.svg" alt="NPM package version." />
</a>
<a href="https://github.com/MaksymBlank/react-native-date-input">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT license." />
</a>

## Examples

<img src="https://react-native-dateinput.s3-us-west-1.amazonaws.com/react-native-dateinput.ios.gif" width="300" alt="React Native Date TextInput on iOS" />

<img src="https://react-native-dateinput.s3-us-west-1.amazonaws.com/react-native-dateinput.android.gif" width="300" alt="React Native Date TextInput on Android" />

## Setup

```bash
npm i --save @maksymblank/react-native-date-input

# --- or ---

yarn add @maksymblank/react-native-date-input
```

## Usage

```javascript
import DateInput from '@maksymblank/react-native-date-input';
...
<DateInput
    mask={'DD/MM/YYYY'}
    onChange={date => console.log(date)}
    validate={false} // true by default
    activeColor={'red'} // #7368FF by default
/>
...
```