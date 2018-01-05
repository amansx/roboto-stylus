# roboto-stylus


``` stylus-lang
$RobotoFontPath = '../../fonts/';

// Import All Typefaces
@import('roboto-stylus')

// Import Individual Typeface
@import('roboto-stylus/roboto')
@import('roboto-stylus/roboto-slab')
@import('roboto-stylus/roboto-condensed')

```

### Import Individual FontFace

``` stylus-lang

Roboto($type: 'Thin',       $weight: 100, $style: normal);
Roboto($type: 'ThinItalic', $weight: 100, $style: italic);

RobotoSlab($type: 'Light',       $weight: 300, $style: normal);
RobotoSlab($type: 'LightItalic', $weight: 300, $style: italic);

```


### Mixin Signature

``` stylus-lang

Roboto(
    $directory = 'roboto', 
    $variant = 'Roboto', 
    $type = 'Regular', 
    $weight = 400, 
    $style = normal
)

```