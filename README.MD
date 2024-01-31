# Checkout page for coffee app

## Adding a web font

You can add a font using Google Web Fonts (lots of ways to do it, Google's is easy) by adding this tag in the <head>

```
<link
  href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap"
  rel="stylesheet"
/>
```

and by adding font-family: 'Open Sans', sans-serif; to whatever you want to change the font to be. You don't have to but it's pretty cool! [Check out Google Fonts][font] if you're curious.

## Overlayed Input

```
<div class="example-group">
  <label for="example" class="input-label">Example Text</label>
  <input id="example" class="example-input" placeholder="try typing here" />
</div>
```

```
<style>
  .example-group {
    position: relative;
    display: inline-block;
  }

  .example-input {
    border-color: crimson;
    padding: 8px;
    border-radius: 5px;
  }

  .input-label {
    background-color: white;
    color: crimson;
    font-size: 11px;
    position: absolute;
    left: 25px;
    top: -7px;
    padding: 0 2px;
  }
</style>
```
