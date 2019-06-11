# react-native-piano [![npm](https://img.shields.io/npm/v/@mrsoneji/react-native-piano.svg?style=flat-square)](https://www.npmjs.com/package/@mrsoneji/react-native-piano)

## Usage

#### Install

npm: `npm i --save react-native-piano`

yarn: `yarn add react-native-piano`

#### Import

ES6 module:

```js
import { Piano } from 'react-native-piano'
```


## Documentation


### Properties

#### Basic

| Prop | Type | Description |
| :------------ |:---------------:| :---------------:|
| noteRange | **Required** `object` | An object representing the range of notes to render. Format `{ first: 48, last: 77 }` in which first and last corresponds to natural notes. |
| onPlayNoteInput | `function` | Function that fires whenever a play-note event is fired. |
| onStopNoteInput | `function` | Function that fires whenever a stop-note event is fired. |

## Questions

Feel free to [contact me](mailto:sebastian.pucheta@gmail.com) or [create an issue](https://github.com/mrsoneji/react-native-piano/issues/new)

> Inspired by [kevinsqi/react-piano](https://github.com/kevinsqi/react-piano).

## License

MIT License