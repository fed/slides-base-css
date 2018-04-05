# slides-base-css

These are just a bunch of base css rules for my slides built with [Remarker](https://github.com/kt3k/remarker).

## Add this project as a dependency

```
yarn add slides-base-css
```

## Linking to the base css file

Make sure to include both the base styles and the local css file on your `remarker.yml` config file:

```yml
cssFiles: [
  './node_modules/slides-base-css/style.css',
  './style.css'
]
```

## Customising colours

On your local `style.css` file, you can add custom styles and customise the colour variables by doing:

```css
:root {
  --color-clear: #fff;
  --color-inverse: #0084ff;
  --color-link: #056cc1;
  --color-text: #1b1b1b;
}
```
