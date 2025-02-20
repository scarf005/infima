# CDN Installation

The quickest way to get started with Infima is to include it directly from a CDN. Add the following `<link>` tag in the `<head>` section of your HTML:

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/infima@0.2.0-alpha.45/dist/css/default/default.css" />
```

## Usage

Once you've included Infima in your project, you can start using its components and utilities right away:

```html
<!doctype html>
<html>
  <head>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/infima@0.2.0-alpha.45/dist/css/default/default.css" />
  </head>
  <body>
    <button class="button button--primary">Click me</button>

    <div class="card">
      <div class="card__header">
        <h3>Card Title</h3>
      </div>
      <div class="card__body">
        <p>Card content goes here.</p>
      </div>
    </div>
  </body>
</html>
```

## Dark Mode Support

To enable dark mode support, include both light and dark themes:

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/infima@0.2.0-alpha.45/dist/css/default/default.css" />
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/infima@0.2.0-alpha.45/dist/css/default/default.dark.css" />
```

Then add the `data-theme="dark"` attribute to your `<html>` or `<body>` tag to activate dark mode:

```html
<html data-theme="dark"></html>
```
