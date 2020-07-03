# SVGSymbolStyling
This repository shows you how to style SVG symbols with CSS. SVG symbols are an extremely popular way of using SVG icons, and is my preferred method most of the time. For a video about how to use SVG Symbol styling, check out our video here:

This demo shows how you can use CSS Variables to style your SVG. For example, you can set the fill color of a path like this:

```html
<path fill="var(--color1)" d="M671.8 403 514.2 490.3l-2.6 179.3L669.1 582.2Z" />
```

Then, simply set the the color in a parent element, like this:

```html
<svg style="--color1: red;">
  <use href="/logo.svg#cube"></use>
</svg>
```

Examples of using the same SVG symbol multiple times with different colors, or changing colors when hovering over the SVG, are covered in the code.