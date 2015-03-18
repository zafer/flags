<img src="http://i.imgur.com/0AEUuks.png" title="The Portugese flag cropped to show detail" />

# World flags

As part of localization at <a href="https://github.com/twiceclothes">Twice</a> (@twiceclothes), I&rsquo;ve created flags for all the countries we ship to. It only represents a small portion of the world&rsquo;s many nations, but I plan to keep adding flags, as well as work with other contributors.

## Primary sources

The flag shape and dimensions are derived from Wikipedia to ensure that they are accurate.

## Why these flags?

Flags are, generally speaking, released in the public domain. And likewise, these files here are released in the public domain as well. 
Countries do have local restrictions on the use of national symbols, though, so please express caution when using these flags for purposes that may seem counter to the respect individuals and nations usually give to their flags.

The main, and frankly, only difference *my* flags have over the thousands of free flag resources is simply color.

I have tried to consistently color the flags, so that instead of many different blues and reds and greens and yellows, there are only a few used (usually a darker and lighter hue).
This works wonderfully to give a consistent look and feel for the flags, as well as avoid the garish eccentricities of coloring you find in &ldquo;accurate&rdquo; flags, e.g. on Wikipedia.

The issue there is that while color for flags has been traditionally defined, digital equivalents do not exist for all nations.
Likewise, the color of cloth for a flag that is flown in the state room for diplomatic receptions, and the flag that is painted on the side of a war-faring vessel are often very dissimilar: one needs to be subdued, and the other needs to be bright.

As such, I feel comfortable in being modestly liberal in my interpretations of color, as well as imposing uniform consistency between flags. The beauty of an open project like this is that we can adjust and tweak color as necessary.

## Currently available flags

* Australia
* Austria
* Belgium
* Bulgaria
* Canada
* Croatia
* Cypress
* Czech Republic
* Denmark
* Estonia
* Finland
* France
* Greece
* Germany
* Hungary
* Ireland
* Italy
* Japan
* Lithuania
* Luxembourg
* Latvia
* Malta
* Mexico
* Netherlands
* New Zealand
* Poland
* Portugal
* Romania
* Slovakia
* Slovenia
* South Korea
* Spain
* Sweden
* United Kingdom
* United States

# Files

Flags are suffixed by their <a href="https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3">ISO 3-digit code</a> (ISO 3166-1 alpha-3).

This initial push of flags represents the countries that Twice (@twiceclothes) currently ships to, so the list is heavily skewed towards Europe for that reason; complete coverage of flags should be expected as time passes.

I plan to have Sketch and Illustrator files available, as well. You can for the most part effectively import SVG files into either program.

## SVG

The SVG files can be easily imported into your favorite graphics program or used directly on the Web. Please note, older versions of mobile Android browsers can have trouble with the width and height of SVG files exported from Adobe Illustrator.

## PNG

The PNG files are provided for convenience, since their fixed raster dimensions will provide little use to most people. Each flag has a variable width based on that nation&rsquo;s standards, but the height of all flags is fixed at 80px.

## Sprite

Again, I have provided the sprite used at Twice for the flags, however, the fixed dimensions will be of limited use for most others. That said, you can use them for a country selector on your site, for example.

Some flags &mdash; those with more than 30% white &mdash; have a faint grey border around them to provide separation from the background (an aesthetic choice to be sure).

The cell size for each part of the sprite is 25px &times; 25px. So your CSS could potentially look like this:

````CSS
.flag {
    width: 25px;
    height: 25px;
    background-image: url("images/localization/sprite_flags.png");
    }
.flag.usa {
    background-position: 0 0;
    }
````````

But it is always more satisfying to make a sprite from scratch and get it feeling just right with your application.
