## Documentation

The inserted text is just placeholders. Use tab to change placeholders.

> The `title` tag will use the folder name.

|  Trigger  | Describe                   |
| --------: | ---------------------------|
| `hbs →`   | `html.base.struct`         |
| `hbr →`   | `html.base.react`          |
| `hca →`   | `html.component.avatar`    |
| `hcc →`   | `html.component.card`      |
| `hcd →`   | `html.component.details`   |
| `hch →`   | `html.component.hero`      |
| `hcl →`   | `html.component.list`      |
| `hcn →`   | `html.component.navbar`    |
| `hct →`   | `html.component.table`     |


## Snippets

### `html.base.struct` | hbs

```html
<!DOCTYPE html>
<html lang='pt-BR'>
	<head>
		<meta charset='utf-8' />
		<meta name='viewport' content='width=device-width' />
		<link rel='icon' href='public/favicon.svg' type='image/svg+xml' />
		<link rel='stylesheet' href='styles.css' />
		<title>{filename}</title>
	</head>
	<body>
		$1
	</body>
</html>
```

### `html.base.react` | hbr

```html
<!DOCTYPE html>
<html lang='pt-BR'>
	<head>
		<meta charset='utf-8' />
		<meta name='viewport' content='width=device-width' />
		<link rel='icon' href='public/favicon.svg' type='image/svg+xml' />
		<title>{filename}</title>
	</head>
	<body>
		<div id='root'></div>

		<script type='module' src='/src/main.tsx'></script>
	</body>
</html>
```

### `html.component.avatar` | hca

```html
<figure>
	<img src='assets/' alt='' />
	<figcaption>name</figcaption>
</figure>
```

### `html.component.card` | hcc

```html
<article>
	<header></header>
	<section></section>
	<footer></footer>
</article>
```

### `html.component.details` | hcd

```html
<details name=''>
	<summary>title</summary>
	<p>body</p>
</details>
```

### `html.component.hero` | hch

```html
<header>
	<figure>
		<img src='assets/' alt='' />
	</figure>

	<section>
		<h2>title</h2>
		<p>description</p>
	</section>
</header>
```

### `html.component.navbar` | hcn

```html
<nav>
	<a href='/'>
		<img src='assets/' alt='' />
	</a>

	<ul>
		<li><a href=''></a></li>
		<li><a href=''></a></li>
		<li><a href=''></a></li>
	 </ul>
</nav>
```

### `html.component.table` | hct

```html
<table>
	<caption>Legend</caption>

	<thead>
		<tr>
			<th>title</th>
			<th>title</th>
			<th>title</th>
		</tr>
	</thead>

	<tbody>
		<tr>
			<td>description</td>
			<td>description</td>
			<td>description</td>
		</tr>
	</tbody>
</table>
```