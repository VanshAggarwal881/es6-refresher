# Es6 refresher
1. let and const instead of var
2. arrow function
***
```bash
let fxn = ()=>{
    console.log('hello')
}
fxn()
```
3. import/export functionality
---
<script type = "module" src = "app.js"></script>
***
one.js
```bash
const obj = {
    myname : 'Vansh'
}

export default obj;
```
app.js
```bash
import obj from './one.js';
console.log(obj.myname);
```
