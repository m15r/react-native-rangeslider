# React Native Range Slider

Installation
---

Using Yarn:
```
yarn add react-native-rangeslider
```

Using NPM:
```
npm install react-native-rangeslider
```

Example
---

```jsx
import RangeSlider from 'react-native-rangeslider'

export default function RangeSliderExample() {

  const handleChange = (values) => {
    // Your logic
  }

  return (
    <RangeSlider
      range={[0,100]}
      defaultValues={[25,75]}
      onChange={handleChange}
      vibrate />
  )
  
}
```

Props
---

Prop          | Description   | Default | Required |
------------- | ------------- | ------------- | ------------- |
range         | Array containing min. and max. values | `[0,100]` | :white_check_mark: |
defaultValues | Initial values for the range slider | `[25,75]` | :white_check_mark: |
onChange      | Returns an array with min. and max. values |
barHeight     | Height of the slider bar | `30` |
barStyle      | Apply custom styling to the bar | `{}` |
handleSize    | Size of the handles | `30` |
handleStyle   | Apply custom styling to the handles | `{}` |
vibrate       | Vibrate when moving the handle | `true` |


