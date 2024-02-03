## Documentation

The inserted text is just placeholders. Use tab to change placeholders.

|  Trigger  | Describe                                   |
| --------: | ----------------------------------------   |
| `tar →`   | `typescript.array.readonly`                |
| `tif →`   | `typescript.type.interface`                |
| `tas →`   | `typescript.type.alias`                    |
| `tun →`   | `typescript.type.union`                    |
| `tup →`   | `typescript.type.tuple`                    |
| `ten →`   | `typescript.type.enum`                     |

## Usage

### `typescript.array.readonly` | tar

```ts
const ${1:identifier}: readonly Array<T> = [$2]
```

### `typescript.type.interface` | tif

```ts
interface ${1:identifier} {
	${2:property}: ${3:type}
}
```

### `typescript.type.alias` | tas

```ts
type ${1:identifier} = $2
```

### `typescript.type.union` | tun

```ts
type ${1:identifier} = $2 | $3
```

### `typescript.type.tuple` | tup

```ts
const ${1:identifier}: readonly [$2, $3] = [$4, $5]
```

### `typescript.type.enum` | ten

```ts
enum ${1:identifier} {
	${2:property} = ${3:value}
}
```