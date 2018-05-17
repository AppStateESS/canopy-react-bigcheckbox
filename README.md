## canopy-react-bigcheckbox

This is a React script for use with AppStateESS/Canopy. It assumes you
have Bootstrap 4 and FontAwesome 5 available.
A class named "pointer" is used.

```
.pointer:hover{cursor:pointer}
```

Example:

```javascript
this.state = {yesFire: true}

const setValue = (val) => {
  this.setState(yesFire : val)
}

<BigCheckbox
  label="Fire Wave Motion Gun" 
  checked={this.state.yesFire} 
  handle={setValue}/>
```
