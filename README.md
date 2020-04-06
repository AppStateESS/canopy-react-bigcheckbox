## canopy-react-bigcheckbox

This is a React script for use with AppStateESS/Canopy. It assumes you
have Bootstrap 4 and FontAwesome 5 available.
A class named "pointer" is used.

```
.pointer:hover{cursor:pointer}
```

Example:

```javascript

import React from 'react'
import BigCheckBox from '@essappstate/canopy-react-bigcheckbox'

class Example extends React.Component {
  constructor(props) {
    super(props)
    this.state = {yesFire: true}
  }

  setValue(val) {
    this.setState(yesFire : val)
  }

  render() {
    return (<BigCheckbox
      label="Fire Wave Motion Gun"
      checked={this.state.yesFire}
      handle={setValue}/>)
  }
}
```
