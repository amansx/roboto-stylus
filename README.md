# Roboto Typeface Stylus Binding
### Roboto is a neo-grotesque sans-serif typeface family developed by Google
[Roboto @Google Fonts](https://fonts.google.com/specimen/Roboto)

``` stylus
$RobotoFontPath = '../../fonts/';

// Import All Typefaces
@import('roboto-stylus')

// Import Individual Typeface
@import('roboto-stylus/roboto')
@import('roboto-stylus/roboto-slab')
@import('roboto-stylus/roboto-condensed')

```

### Import Individual Font-Faces

``` stylus
// Set your Font Path
$RobotoFontPath = '../../fonts/';

// Import the Mixin
@import('roboto-stylus/roboto-mixins')

// Look at roboto.styl for more variants
Roboto($type: 'Thin',       $weight: 100, $style: normal);
Roboto($type: 'ThinItalic', $weight: 100, $style: italic);

// Look at roboto-slab.styl for more variants
RobotoSlab($type: 'Light',       $weight: 300, $style: normal);
RobotoSlab($type: 'LightItalic', $weight: 300, $style: italic);

```

### Mixin Signature

``` stylus

Roboto(
    $directory = 'roboto', 
    $variant = 'Roboto', 
    $type = 'Regular', 
    $weight = 400, 
    $style = normal
)

```