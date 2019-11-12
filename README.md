## Introduction

Izmir is a mini CSS library allowing you to quickly create beautiful image hover elements. Packed with a host of styling classes and custom properties, Izmir allows you total control and almost limitless possibilites. Simply load the CSS library in to your project, add the element markup combined with the style classes of your choice to custom build your perfect image hover effect.

## Features

* 1000's of possible style combinations
* 20 animated border effects
* 9 animated image effect
* 12 animated text effects
* Overlay style classes
* Animation delay classes
* Text layout classes
* Collection of custom properties to further custom style your element
  * Border width
  * Border margin
  * Border color
  * Primary color
  * Secondary color
  * Text color
  * Image hover opacity
  * Image hover color
  * Image hover gradient
* Accesible (hover triggered on focus)
* Ultra small file size (2KB GZipped)
* Complete documentation

## NPM

  ```
  npm install @ciar4n/izmir
  ```

## Setup

1. Extract and copy the CSS files in the root of your download folder to your projects CSS folder.
2. Include a link to the CSS your document's `<head>` tags

```html
<link rel="stylesheet" href="css/izmir.min.css">
```

3. Use the following markup to create the most basic instance of an image hover element..

```html
<figure class="c4-izmir">
  <img src="https://source.unsplash.com/FaPxZ88yZrw/400x300" alt="Sample Image">
  <figcaption>
      <h3>
        Some sample text
      </h3>
    </div>
</figure>
```

## License

Izmir CSS Library is licensed under the MIT license. (http://opensource.org/licenses/MIT)
