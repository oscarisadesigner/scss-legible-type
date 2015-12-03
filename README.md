# scss-legible-type
Sass mixin that alters letter-spacing on font-size

## Purpose

This mixin creates more readable text by altering spacing between characters usually named tracking in typography terms. As you increase the font-size, the letter-spacing increases.

Great visual demonstration on type legibility is Apple's WWDC 2015 Session: Introducing the New System Fonts presented by Antonio Cavedoni; https://developer.apple.com/videos/play/wwdc2015-804/

## Usage

Import the _legible.scss file and declare your font-size and it'll automagically set the letter-spacing for you:-

<code>h1 {
    @include font-size(16px);
}
</code>

## Notes

The mixin only applies to font-sizes that are less than 18px since this is intended for body type. Relative <code>em</code>s are also built in for better scalability when zooming in/out pages.

## Caveats

Every font/type family is designed differently and this mixin may not work for some type families. As of this moment, there's no way to alter the scaling on the letter-spacing and may be added in a future update.
