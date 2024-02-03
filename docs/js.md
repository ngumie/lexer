## Documentation

The inserted text is just placeholders. Use tab to change placeholders.

> Select the array of elements and provide the snippet.

|  Trigger  | Describe                                   |
| --------: | ----------------------------------------   |
| `fof →`   | `for.of`                                   |
| `fin →`   | `for.in`                                   |
| `fec →`   | `[].forEach`                               |
| `fet →`   | `[].find`                                  |
| `fma →`   | `[].map`                                   |
| `fre →`   | `[].reduce`                                |
| `fil →`   | `[].filter`                                |
| `fso →`   | `[].some`                                  |
| `fsr →`   | `[].sort`                                  |
| `fid →`   | `[].indexOf`                               |
| `fic →`   | `[].includes`                              |
| `fwi →`   | `[].with`                                  |
| `fsp →`   | `[].splice`                                |
| `fsl →`   | `[].slice`                                 |
| `fps →`   | `[].push`                                  |
| `fpo →`   | `[].pop`                                   |
| `fco →`   | `[].concat`                                |
| `fen →`   | `[].entries`                               |
| `fev →`   | `[].every`                                 |
| `fjo →`   | `[].join`                                  |

## Snippet

### `for.of` | fof

```js
for (const ${1:element} of ${2:array}) { ${3:expression} }
```

### `for.in` | fin

```js
for (const ${1:element} in ${2:array}) { ${3:expression} }
```

### `.forEach` | fec

```js
array.forEach((${1:element}, ${2:index}, ${3:array}) => { ${4:expression} }, ${5:thisArg})
```

### `.find` | fet

```js
array.find((${1:element}, ${2:index}, ${3:array}) => { ${4:expression} })
```

### `.map` | fma

```js
array.map((${1:element}, ${2:index}, ${3:array}) => { ${4:expression} })
```

### `.reduce` | fre

```js
array.reduce((${1:accumulator}, ${2:currentValue}, ${3:currentIndex}, ${4:array}) => { ${5:expression} }, ${6:initialValue})
```

### `.filter` | fil

```js
array.filter((${1:element}, ${2:index}, ${3:array}) => { ${4:condition} })
```

### `.some` | fso

```js
array.some((${1:element}, ${2:index}, ${3:array}) => { ${4:condition} })
```

### `.sort` | fsr

```js
array.sort(${1:compareFn})
```

### `.indexOf` | fid

```js
array.indexOf(${1:searchElement}, ${2:fromIndex})
```

### `.includes` | fic

```js
array.includes(${1:searchElement}, ${2:fromIndex})
```

### `.with` | fwi

```js
array.with(${1:index}, ${2:value})
```

### `.splice` | fsp

```js
array.splice(${1:index}, ${2:deleteCount}, ${3:addElement})
```

### `.slice` | fsl

```js
array.slice(${1:start}, ${2:end})
```

### `.push` | fps

```js
array.push(${1:element})
```

### `.pop` | fpo

```js
array.pop()
```

### `.concat` | fco

```js
array.concat(${1:array})
```

### `.entries` | fen

```js
const $1 = array.entries()
```

### `.every` | fev

```js
array.every((${1:current}) => { ${2:condition} })
```

### `.join` | fjo

```js
array.join(${1:separator})
```
