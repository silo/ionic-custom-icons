# Custom ionic icons from SVG files

## DO NOT USE, DEPRECATED

### Usage
```
HTML:
<ion-icon name="dsb-crown" item-start></ion-icon>
```

#### Default
```
CSS:
@include makeIcon(crown);
```

#### Change color
```
CSS:
@include makeIcon(crown, orange);
```

#### Change file name to be different from ionic html naming
```
CSS:
@include makeIcon(crown, orange, icon-crown); // if file is named icon-crown.svg
```

### Only change file name but keep default color
```
CSS:
@include makeIcon(crown, default, icon-crown); // if file is named icon-crown.svg
```

### Settings
```
CSS:

$icon-size: 0.9em; // change width to get same size as the default icon set from ionic
$icon-prefix: dsb; // change naming convention in the icon.scss file
```


## Have fun 
