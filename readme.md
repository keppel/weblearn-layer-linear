## weblearn-layer-linear

Simple fully-connected layer for [WebLearn]

### Usage
```
npm install weblearn-layer-linear
```

```js
const Linear = require('weblearn-layer-linear')

const inputSize = 2
const outputSize = 10
const hasBias = true

const layer = Linear(inputSize, outputSize, hasBias)
```

[WebLearn]: https://github.com/keppel/weblearn
