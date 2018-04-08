# matriphe-scss

This is a basic SCSS template file used for matriphe's web products.

## Installation

Using `yarn`
```
yarn add --dev matriphe-scss
```

Or using `npm`
```
npm install --dev matriphe-scss
```

### For Laravel Using Bulma

Install Bulma using `yarn` or `npm`, and then copy the `bulma.scss` to resources assets folder.

```
cp node_modules/matriphe-scss/bulma/bulma.scss resources/assets/sass/bulma.scss
```

On the `app.scss`, load the copied `bulma.scss` file.

```
@import "bulma.scss";
```