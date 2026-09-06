 # Sample HTML and CSS Program

This example demonstrates a simple HTML page styled with CSS.

## HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Welcome Page</title>
	<link rel="stylesheet" href="styles.css">
</head>
<body>
	<div class="card">
		<h1>Welcome</h1>
		<p>This is a sample page built with HTML and CSS.</p>
		<button>Learn More</button>
	</div>
</body>
</html>
```

## CSS (`styles.css`)

```css
body {
	margin: 0;
	min-height: 100vh;
	display: grid;
	place-items: center;
	font-family: Arial, sans-serif;
	background: #f0f4f8;
}

.card {
	padding: 2rem;
	text-align: center;
	background: white;
	border-radius: 12px;
	box-shadow: 0 4px 12px rgb(0 0 0 / 15%);
}

button {
	padding: 0.7rem 1rem;
	color: white;
	background: #2563eb;
	border: 0;
	border-radius: 6px;
	cursor: pointer;
}
```

The HTML provides the page structure, while CSS controls its layout, colors, spacing, and appearance.
