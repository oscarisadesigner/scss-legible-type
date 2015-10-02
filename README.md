# legible-type-scss
Alters body type tracking according to font size

## Purpose

Tracking is the spacing between characters in typography, the problem with smaller type sizes is that the spacing gets tighter and makes it harder to read. The mixin I created does the opposite, as you decrease the font-size, you increase the tracking. Therefore making it more readable thus, more legible.

Great visual demonstration on type legibility is Apple's WWDC 2015 Session: Introducing the New System Fonts presented by Antonio Cavedoni; https://developer.apple.com/videos/play/wwdc2015-804/

## Usage

Import the legible.scss file and declare your font-size as so:-
<code>@include font-size(16px)</code>

## Notes

The mixin only applies to body type, a font-size that is less than 18px. Also, this mixin has <code>rem</code>s built in for better scalability when zooming in/out pages.

## Caveats

Every font/type family is designed differently and this mixin may not work for some type families. As of this moment, there's no way to alter the scaling on the tracking and may be added in a future update.
