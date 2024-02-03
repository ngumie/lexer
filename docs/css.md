## Documentation

The inserted text is just placeholders. Use tab to change placeholders.

|  Trigger  | Describe                                   |
| --------: | ----------------------------------------   |
| `csa →`   | `css.selector.attribute`                   |
| `csab →`  | `css.selector.attribute.begins`            |
| `csac →`  | `css.selector.attribute.contains`          |
| `csae →`  | `css.selector.attribute.ends`              |
| `cac →`   | `css.align.center`                         |
| `cae →`   | `css.align.end`                            |
| `cas →`   | `css.align.start`                          |
| `clf →`   | `css.layout.flex`                          |
| `clg →`   | `css.layout.grid`                          |
| `cbr →`   | `css.border.rounded`                       |
| `cre →`   | `css.reset`                                |
| `crl →`   | `css.reset.link`                           |
| `cri →`   | `css.reset.image`                          |
| `crb →`   | `css.reset.button`                         |
| `crli →`  | `css.reset.list`                           |
| `can →`   | `css.animation`                            |
| `cat →`   | `css.animation.transition`                 |
| `cak →`   | `css.animation.keyframe`                   |
| `ctt →`   | `css.transform.translate`                  |
| `ctr →`   | `css.transform.rotate`                     |
| `cts →`   | `css.transform.scale`                      |
| `ctk →`   | `css.transform.skew`                       |
| `crc →`   | `css.responsive.container`                 |
| `crm →`   | `css.responsive.media`                     |

## Snippets

### `css.selector.attribute` | csa

```css
[${1:checked}] { ${2:rules} }
```

### `css.selector.attribute.begins` | csab

```css
[data-^='${1:value}'] { ${2:rules} }
```

### `css.selector.attribute.contains` | csac

```css
[data-*='${1:value}'] { ${2:rules} }
```

### `css.selector.attribute.ends` | csae

```css
[data-$='${1:value}'] { ${2:rules} }
```

### `css.align.center` | cac

```css
 {
    display: flex;
    align-items: center;
    justify-content: center;
}
```

### `css.align.end` | cae

```css
 {
    display: flex;
    align-items: center;
    justify-content: end;
}
```

### `css.align.start` | cas

```css
 {
    display: flex;
    align-items: center;
    justify-content: start;
}
```

### `css.layout.flex` | clf

```css
 {
    display: flex;
    align-items: ${[start, center, end, stretch, baseline]};
    justify-content: ${[start, center, end, space-around, space-evenly, space-between]};
    flex-wrap: wrap;
    gap: ${5:value};
}
```

### `css.layout.grid` | clg

```css
 {
    display: grid;
    grid-template-columns: repeat(auto-${[fill, fit]}, minmax(${2:min}, ${3:max}));
    grid-auto-rows: ${4:value};
    gap: ${5:value};
}
```

### `css.border.rounded` | cbr

```css
 {
    border-radius: 8px;
    border: 1px solid $#f1f5f9;
}
```

### `css.reset` | cr

```css
*,
*::before,
*::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    line-height: 1.5;

    font-size: 62.5%;
    font-family: system-ui, sans-serif;
    font-synthesis: none;

    text-wrap: balance;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

### `css.reset.link` | crl

```css
a {
	color: inherit;
	text-decoration: 2px underline wavy $#f5a7ca;

	${1:rules}
}
```

### `css.reset.image` | cri

```css
img {
	display: block;

	height: auto;
	max-width: 100$;
	object-fit: cover;

	${1:rules}
}
```

### `css.reset.button` | crb

```css
button {
	display: block;

	cursor: point;
	border: 1px solid $#f1f5f9;

	${1:rules}
}
```

### `css.reset.list` | crli

```css
ul {
	list-style: none;

	${1:rules}
}
```

### `css.animation` | can

```css
 {
    animation: ${1:name}, ${2:duration} ${[ease, linear, ease-in, ease-out, ease-in-out]}
            ${4:delay} ${5:infinite} ${[normal, reverse, alternate] $[none, forwards, backwards,
        both]};
}
```

### `css.animation.transition` | cat

```css
 {
    transition: ${1:property}, ${2:duration} ${[ease, linear, ease-in, ease-out, ease-in-out]};
}
```

### `css.animation.keyframe` | cak

```css
@keyframes ${1:identifier} {
	from { ${2:rules} }
	to { ${3:rules} }
}
```

### `css.transform.translate` | ctt

```css
 {
    translate: ${1:x}, ${2:y};
}
```

### `css.transform.rotate` | ctr

```css
 {
    rotate: ${1:value};
}
```

### `css.transform.scale` | cts

```css
 {
    scale: ${1:value};
}
```

### `css.transform.skew` | ctk

```css
 {
    skew: ${1:value};
}
```

### `css.responsive.container` | crc

```css
@container (max-width: ${1:breakpoint}) {
	${2:element} { ${3:rules} }
}
```

### `css.responsive.media` | crm

```css
@media (max-width: ${1:breakpoint}) {
	${2:element} { ${3:rules} }
}
```