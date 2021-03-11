# vim-js-snippets
My favorite JS snippets for (neo)vim!

## Database snippets

### [Op] Sequelize.Op

```javascript
const Op = require('sequelize').Op
```

### [Op.eq] Sequelize.eq

```javascript
$1: {
  [Op.eq]: $2
}
```

### [Op.in] Sequelize.in

```javascript
$1: {
  [Op.in]: $2
}
```

### [oid] ObjectId

```javascript
ObjectId($1)
```

### [roid] mongoose require ObjectId

```javascript
const ObjectId = require('mongoose').Types.ObjectId
```

## Javascript

### [js] JSON.stringify

```javascript
JSON.stringify($1, null, 2)
```

### [jp] JSON.parse

```javascript
JSON.parse($1)
```

### [hop] hasOwnProperty

```javascript
hasOwnProperty($1)
```

### [me] module.exports

```javascript
module.exports = $0
```

### [ex] exports

```javascript
exports $0
```

### [cr] const x = require(y)

```javascript
const $1 = require('$1')
```

### [im] import x from y
```javascript
import $1 from $2
```

### [imo] import { x } from y
```javascript
import { $1 } from $2
```

### [cl] console.log

```javascript
console.log($1)
```

### [cw] console.warn

```javascript
console.warn($1)
```

### [c] const x = y

```javascript
const $1 = $0
```

### [l] let x = y

```javascript
let $1 = $0
```

### [if] if

```javascript
if ($1) {
	${0:${VISUAL}}
}
```

### [fun] function

```javascript
function $1 ($2) {
	${0:${VISUAL}}
}
```

### [af] arrow function

```javascript
($1) => {
	${0:${VISUAL}}
}
```

### [mf] prototype method function

```javascript
$1.prototype.$2 = function $2 ($4) {
${0:${VISUAL}}
}
```

## Test snippets

### [des] describe()

```javascript
describe('$1', () => {
	${0:${VISUAL}}
})
```

### [it] it()

```javascript
it('$1', () => {
	${0:${VISUAL}}
})
```

### [test] test()

```javascript
test('$1', () => {
	${0:${VISUAL}}
})
```
