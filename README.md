# interactive_data_visualization._JS


## Description
This README file provides information about the JavaScript code associated with the provided CSS styles. The code is designed to apply styling to HTML elements using CSS rules.

## CSS Styles
The following CSS styles are defined in the JavaScript code:

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.chart-container {
  max-width: 600px;
  margin: 0 auto;
}
```

### Universal Selector (`*`)
- The universal selector `*` is used to target all HTML elements on the page.
- The `margin` property is set to `0`, which removes any default margin from all elements.
- The `padding` property is set to `0`, which removes any default padding from all elements.
- The `box-sizing` property is set to `border-box`, which ensures that the element's total width and height include the padding and border.

### Class Selector (`.chart-container`)
- The class selector `.chart-container` is used to target elements with the `class` attribute set to `chart-container`.
- The `max-width` property is set to `600px`, limiting the maximum width of elements with this class to 600 pixels.
- The `margin` property is set to `0 auto`, which horizontally centers elements with this class within their parent container.

## Usage
You can use this CSS code in your HTML documents by linking to an external CSS file or by embedding it within a `<style>` tag in your HTML document's `<head>` section.

### Linking to an External CSS File
To use these styles by linking to an external CSS file, follow these steps:

1. Create a CSS file (e.g., `styles.css`) and copy the CSS code into this file.
2. In your HTML document's `<head>` section, add the following line to link to the external CSS file:

```html
<link rel="stylesheet" type="text/css" href="styles.css">
```

Replace `"styles.css"` with the actual path to your CSS file.

### Embedding CSS in HTML
To use these styles by embedding them in your HTML document, follow these steps:

1. In your HTML document's `<head>` section, add a `<style>` tag:

```html
<style>
  /* Paste the CSS code here */
</style>
```

2. Copy the CSS code and paste it within the `<style>` tag.

## License
This JavaScript and CSS code are provided under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

Please feel free to reach out if you have any questions or need further assistance with this code.
