
# monkeys-native-toolbox
[**IMPORTANT**] This toolbox is in under heavy development right now. You should wait until published on npm. The responsibility is yours.

Toolbox for react native. It allows you to build react-native apps faster than before.

# Installation
`npm install melihmucuk/monkeys-native-toolbox --save`

# API Reference
API reference divided by two parts.

  * Components
    * [Button](https://github.com/melihmucuk/monkeys-native-toolbox#button-)
    * [MTextInput](https://github.com/melihmucuk/monkeys-native-toolbox#mtextinput-)

## Components

### `<Button />`

A button component that accepts left & right icon.

**Example**
```javascript
<Button
 leftIcon={{uri:  'your icon uri'}}
 rightIcon={{uri:  'your icon uri'}}
>
  Hello World
</Button>
```

**Props**
 
 * `leftIcon` (optional): Left icon of the button. It works like `Image` source props.
 * `leftIconStyle` (optional): Style of the left icon. It works like `Image` style.
 * `rightIcon` (optional): Right icon of the button. It works like `Image` source props.
 * `rightIconStyle` (optional): Style of the right icon. It works like `Image` style.
 * `containerStyle` (optional): Style of the button container. It works like `TouchableOpacity` style.
 * `textStyle` (optional): Style of the button text. It works like `Text` style.

 ### `<MTextInput />`

A TextInput component that accepts left & right icon with onPress event.

**Example**
```javascript
<MTextInput 
 leftIcon={{uri: 'your icon uri'}} 
 leftIconOnPress={() => alert('Left icon pressed!')}
 rightIcon={{uri: 'your icon uri'}} 
 rightIconOnPress={() => alert('Right icon pressed!')}
 placeholder={'Hello'} 
/>
```

**Props**
 
 * `leftIcon` (optional): Left icon of the input. It works like `Image` source props.
 * `leftIconStyle` (optional): Style of the left icon. It works like `Image` style.
 * `leftIconOnPress` (optional): A function that runs when left icon pressed.
 * `rightIcon` (optional): Right icon of the input. It works like `Image` source props.
 * `rightIconStyle` (optional): Style of the right icon. It works like `Image` style.
 * `rightIconOnPress` (optional): A function that runs when right icon pressed.
 * `containerStyle` (optional): Style of the input container. It works like `View` style.
 * `inputStyle` (optional): Style of the input. It works like `TextInput` style.