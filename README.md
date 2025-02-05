# My Project

## The elements

The project consists of a header , footer , h1 and input field.
```html
<div>
    <h1>{greeting}</h1>
    <h2>What do you want to write?</h2>
    <input type = "text" bind:value={greeting}>
    </div>
```

## The purpose of the project

The purpose is for the h1 to change based on what the input is.

```javascript
<script>
	import '../app.css'; // Creates a connection to app.css
	let { children } = $props(); // Props means properties
</script>

{@render children()}
```
