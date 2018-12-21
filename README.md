# Daf Converter

Convert daf pages to numbers and vice-versa

A daf is a the hebrew word for a page. It usally refers to pages in the talmud. Pages are numbered using [Gematriya/Gematria](https://en.wikipedia.org/wiki/Gematria), or perhaps more accurately, [Hebrew numerals](https://en.wikipedia.org/wiki/Hebrew_numerals). It is a system of writing numbers as Hebrew letters. This JavaScript module allows for easy conversion between gematriya and JavaScript `Number` types.

This code was originally written for [js-gematriya](https://github.com/Scimonster/js-gematriya) which is an abastraction from
[hebcal/hebcal-js](https://github.com/hebcal/hebcal-js).

## Install

Install daf-coverter by running `npm install daf-converter` or from it's Github repository by running `git clone git@github.com:peacestone/daf-converter.git`

## API

On the client side, the API is available through the global function `convertDaf`. In Node, `require('convertDaf')`.

A single function is available. Pass it a `Number` or `String`. Given a number, it will return the string representation. Given a daf string, it will return the number it represents. Here is an example:

```js
convertDaf(118)
> 'קיח'
convertDaf('עד')
> 74
```

## License

Licensed MIT
