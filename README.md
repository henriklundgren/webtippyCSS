# webtippy

## Information
Simple and straightforward object oriented CSS to declare one of the 4 major websafe font families.

## Usage
* Make sure your main css file have *no* font families declared. Unless you have some specific element that isnt declared through the usual channels..
* Add the webtippy.css in your HTML HEAD.
* Call the class webtippy + font-family on the container tag. This should usually be the body. 

## Notes
Most common fallback fonts on Linux are Type 1 fonts. Some OS config settings might reject them. I will look further into this as time permits.

CSS3 font-size-adjust is only supported on Firefox.
