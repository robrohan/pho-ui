# pho-ui

Pho-ui is just a stylesheet that styles the default HTML controls into something that looks basic but useable. It also allows you to extend it with just plain old CSS (if you know how to use CSS).

The sheet is only ~400 lines, so you can use it as a starter kit if you like, but you can just override anything using your own sheet on top of it.

Pho-ui styles default HTML elements - things like buttons, text areas, drop downs, checkboxes and radio buttons. You don't have to use any special classes or do anything like that - just write HTML.

It is meant to be something you can just drop into any web project and have something useable that you can iterate on.

## Usage

Just include it:

```html
<head>
  <link rel="stylesheet" type="text/css" href="src/pho-ui.css" />
</head>
```

Then build your UI with standard HTML tags.

You can override colors, by overriding the root variables:

```css
:root {
  --main-font: "courier";
  --select-focus: black;
  --color-control: silver;
}
```

See the examples.
