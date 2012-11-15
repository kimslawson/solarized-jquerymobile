# Solarized theme for jQuery Mobile
Solarized for jQuery Mobile is a jQuery Mobile theme by Kim Slawson based on Ethan Schoonover's remarkable [Solarized color palette](http://ethanschoonover.com/solarized). I made it because I thought jQuery Mobile's default swatches were a big garish. I must express thanks to the jQuery team for [jQuery Mobile](http://jquerymobile.com/) and [ThemeRoller](http://jquerymobile.com/themeroller/index.php), and my undying gratitude to Ethan Schoonover for the [Solarized](http://ethanschoonover.com/solarized) colorscheme.

## Variants
Solarized for jQuery Mobile comes in two variants, separated to save file size and bandwidth. `solarized` has only the light version of the colorscheme, whereas `solarized-unified` brings both the light and dark sides of the force together.

Both variants come in regular (`.css`) and minified (`.min.css`) versions. If bandwidth or file size is a primary concern, use the minified version. If readability is desired, use the regular version.

## Getting it
There are two ways to get this jQuery Mobile theme:

* download the [zipfile or tar.gz](https://github.com/kimslawson/solarized-jquerymobile/downloads), or
* check out the repository

        git clone git://github.com/kimslawson/solarized-jquerymobile.git

## Installation
1. Get the theme via one of the methods above.
2. If this is your first blush theming your jQuery Mobile installation, then copy the "css" directory along with its contents to the root level of your jQuery Mobile installation.

 If you already have a "css" directory at the root level of your jQuery Mobile installion, then copy the desired theme variant(s) into your "css" directory.
 
## Using the theme
Directions for including jQuery Mobile in your project are beyond the scope of this document. Detailed instructions can be found on the [jQuery Mobile site](http://jquerymobile.com/). Please choose one of the following:

### If you wish to use only the light variant
Add the following line BEFORE the other jQuery Mobile stylesheet links:

    <link rel="stylesheet" href="/css/solarized.css" />

### If you wish to use the "Unified" variant
For access to both the light and dark side of the force, add the following line BEFORE the other jQuery Mobile stylesheet links:

    <link rel="stylesheet" href="/css/solarized-unified.css" />
 
## Theme swatches

The following light swatches are available in the `solarized` variant. These display the color listed on the light background, #eee8d5 for headers and #fdf6e3 for content.

* A &mdash; Yellow (#b58900)
* B &mdash; Orange (#cb4b16)
* C &mdash; Red (#dc322f)
* D &mdash; Magenta (#d33682)
* E &mdash; Violet (#6c71c4)
* F &mdash; Blue (#268bd2)
* G &mdash; Cyan (#2aa198)
* H &mdash; Green (#859900)
* I &mdash; Grey (monochromatic: #586e75)

In addition to the swatches listed above, the `solarized-unified` variant includes these dark swatches. These show the following colors on a dark background, using #073642 for headers and #002b36 for content.

* J &mdash; Yellow (#b58900)
* K &mdash; Orange (#cb4b16)
* L &mdash; Red (#dc322f)
* M &mdash; Magenta (#d33682)
* N &mdash; Violet (#6c71c4)
* O &mdash; Blue (#268bd2)
* P &mdash; Cyan (#2aa198)
* Q &mdash; Green (#859900)
* R &mdash; Grey (monochromatic: #586e75)

## Troubleshooting
If, after installation, you have issues with the theme, try the following:

* Make sure the files are in the places indicated above in "Installation". If they are not, you may not see any evidence of the theme, or you may not see any of the icons.
* Make sure you reference the theme's css file in the place indicated above in "Using the theme". Things will look odd if you link to the theme stylesheet after the jQuery Mobile stylesheets.
* As always, if you are still stumped, check Stack Overflow and Google :-)

# Bugs & Improvements

Please [report any issues](https://github.com/kimslawson/solarized-jquerymobile/issues) you find on github. If you've added some improvements and you want them included, then please send me a patch or a GitHub pull request.

# Contact

- [Kim Slawson](http://slawson.org/)