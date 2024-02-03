## Documentation

The inserted text is just placeholders. Use tab to change placeholders.

> The component name will match the file name.

|  Trigger  | Describe (stateless)                       |
| --------: | ----------------------------------------   |
| `sfc →`   | `stateless.function.component`             |
| `sfcp →`  | `stateless.function.component.props`       |
| `safc →`  | `stateless.arrow.function.component`       |
| `safcp →` | `stateless.arrow.function.component.props` |

| Trigger   | Describe                                   |
| --------: | ----------------------------------------   |
| `rfc →`   | `react.function.component`                 |
| `rfcp →`  | `react.function.component.props`           |
| `rafc →`  | `react.arrow.function.component`           |
| `rafcp →` | `react.arrow.function.component.props`     |

## React with JavaScript

### `stateless.function.component` | sfc

```jsx
export default function ${1:filename}() {
	return $1
}
```

### `stateless.function.component.props` | sfcp

```jsx
import PropTypes from 'prop-types'

export default function ${1:filename}({}) {
	return $1
}

${1:filename}.propType = {}
```

### `stateless.arrow.function.component` | safc

```jsx
export const ${1:filename} = () => {
	return $1
}
```

### `stateless.arrow.function.component.props` | safcp

```jsx
import PropTypes from 'prop-types'

export const ${1:filename} = ({}) => {
	return $1
}

${1:filename}.propType = {}
```


### `react.function.component` | rfc

```jsx
import { useState } from 'react'

export default function ${1:filename}() {
	const [$2, set$2] = useState($3)

	return $4
}
```

### `react.function.component.props` | rfcp

```jsx
import { useState } from 'react'
import PropTypes from 'prop-types'

export default function ${1:filename}({}) {
	const [$2, set$2] = useState($3)

	return $4
}

${1:filename}.propType = {}
```

### `react.arrow.function.component` | rafc

```jsx
import { useState } from 'react'

export const ${1:filename} = () => {
	const [$2, set$2] = useState($3)

	return $4
}
```

### `react.arrow.function.component.props` | rafcp

```jsx
import { useState } from 'react'
import PropTypes from 'prop-types'

export const ${1:filename} = () => {
	const [$2, set$2] = useState($3)

	return $4
}

${1:filename}.propType = {}
```

## React with TypeScript

### `stateless.function.component` | sfc

```tsx
export default function ${1:filename}() {
	return $1
}
```

### `stateless.function.component.props` | sfcp

```tsx
type ${1:filename}Pros = {}

export default function ${1:filename}({}) {
	return $1
}
```

### `stateless.arrow.function.component` | safc

```tsx
import { type FC } from 'react'

export const ${1:filename}: FC = () => {
	return $1
}
```

### `stateless.arrow.function.component.props` | safcp

```tsx
import { type FC } from 'react'

type ${1:filename}Pros = {}

export const ${1:filename}: FC<${1:filename}> = ({}) => {
	return $1
}
```


### `react.function.component` | rfc

```tsx
import { useState } from 'react'

export default function ${1:filename}() {
	const [$2, set$2] = useState($3)

	return $4
}
```

### `react.function.component.props` | rfcp

```tsx
import { useState } from 'react'

type ${1:filename}Pros = {}

export default function ${1:filename}({}: ${1:filename}Pros) {
	const [$2, set$2] = useState($3)

	return $4
}s
```

### `react.arrow.function.component` | rafc

```tsx
import { type FC, useState } from 'react'

export const ${1:filename}: FC = () => {
	const [$2, set$2] = useState($3)

	return $4
}
```

### `react.arrow.function.component.props` | rafcp

```tsx
import { type FC, useState } from 'react'

type ${1:filename}Pros = {}

export const ${1:filename}: FC<${1:filename}Pros> = ({}) => {
	const [$2, set$2] = useState($3)

	return $4
}
```