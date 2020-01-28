# stepbar

> stebar element for declared ui flow sequence for every app step

## Install

```bash
npm install --save ui-stepbar
```

## Usage

```jsx
import React, { Component } from 'react'

import Stepbar from 'stepbar'

class Example extends Component {
  const items = [{id:1, name: 'test'}]

  render () {
    return (
      <Selector
        items={items}
        label="Options"
        placeholder="Select one option..."
      />
    )
  }
}
```
#### Note:

If the example project doesn't run or throws this message:

```
You might have more than one copy of React in the same app
```
 
Run the following code inside the example project:
```
npm link ../node_modules/react
``` 

## License

MIT © [kikoken](https://github.com/kikoken)
