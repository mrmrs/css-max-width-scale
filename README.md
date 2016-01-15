# css-max-width-scale 0.0.6

Css module of single purpose classes for max width scale

#### Stats

286 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-max-width-scale
```

#### With Git

```
git clone https://github.com/tachyons-css/css-max-width-scale
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-max-width-scale";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-max-width-scale">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MAX WIDTH - SCALE
*/
.mx-wi1 { max-width: 1rem; }
.mx-wi2 { max-width: 2rem; }
.mx-wi3 { max-width: 4rem; }
.mx-wi4 { max-width: 8rem; }
.mx-wi5 { max-width: 16rem; }
.mx-wi6 { max-width: 32rem; }
.mx-wi7 { max-width: 48rem; }
.mx-wi8 { max-width: 64rem; }
.mx-wi9 { max-width: 96rem; }
.mx-wi10 { max-width: 128rem; }
@media screen and (min-width: 48em) {
 .mx-wi1-ns { max-width: 1rem; }
 .mx-wi2-ns { max-width: 2rem; }
 .mx-wi3-ns { max-width: 4rem; }
 .mx-wi4-ns { max-width: 8rem; }
 .mx-wi5-ns { max-width: 16rem; }
 .mx-wi6-ns { max-width: 32rem; }
 .mx-wi7-ns { max-width: 48rem; }
 .mx-wi8-ns { max-width: 64rem; }
 .mx-wi9-ns { max-width: 96rem; }
 .mx-wi10-ns { max-width: 128rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mx-wi1-m { max-width: 1rem; }
 .mx-wi2-m { max-width: 2rem; }
 .mx-wi3-m { max-width: 4rem; }
 .mx-wi4-m { max-width: 8rem; }
 .mx-wi5-m { max-width: 16rem; }
 .mx-wi6-m { max-width: 32rem; }
 .mx-wi7-m { max-width: 48rem; }
 .mx-wi8-m { max-width: 64rem; }
 .mx-wi9-m { max-width: 96rem; }
 .mx-wi10-m { max-width: 128rem; }
}
@media screen and (min-width: 64em) {
 .mx-wi1-l { max-width: 1rem; }
 .mx-wi2-l { max-width: 2rem; }
 .mx-wi3-l { max-width: 4rem; }
 .mx-wi4-l { max-width: 8rem; }
 .mx-wi5-l { max-width: 16rem; }
 .mx-wi6-l { max-width: 32rem; }
 .mx-wi7-l { max-width: 48rem; }
 .mx-wi8-l { max-width: 64rem; }
 .mx-wi9-l { max-width: 96rem; }
 .mx-wi10-l { max-width: 128rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

