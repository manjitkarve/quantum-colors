Quantum-Colors

## Description
Use the color palette from Google's [Material Design](http://www.google.com/design/spec/style/color.html#color-ui-color-palette) spec in your Sass projects.

## What it is
Picked up the colors from https://github.com/nickpfisterer/quantum-colors 
Added maps for individual color palettes
Added functions to define palettes and retreive palette colors

## Usage
Import "quantum-colors" into your sass file
```scss
@import "quantum-colors";
```
Modify it to define your palette instead of the cyan-yellow-orange palette currently defined.
```scss
$primary: create-palette($blue-pal);
```
Use functions "xdark-pal", "dark-pal", "base-pal", "light-pal", "xlight-pal" to use colors in your project. For example:
```scss
.myHeader{
    background-color: base-pal($primary);
}
```

## ChangeLog
**v1.0.0** (06-25-2015):
* First release