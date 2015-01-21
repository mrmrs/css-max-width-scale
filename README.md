# CSS MAX WIDTH SCALE

  Mobile-first classes for css-max-width-scale.
  Set the desired css-max-width-scale on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-max-width-scale
```
View on [npm](https://www.npmjs.org/package/css-max-width-scale)


## File Size

1.6K max-width-scale.css
1.1K max-width-scale.min.css
241B minified and gzipped

## The Code
```
.mx-wi1  {  max-width: 1rem; }
.mx-wi2  {  max-width: 2rem; }
.mx-wi3  {  max-width: 4rem; }
.mx-wi4  {  max-width: 8rem; }
.mx-wi5  {  max-width: 16rem; }
.mx-wi6  {  max-width: 32rem; }
.mx-wi7  {  max-width: 48rem; }
.mx-wi8  {  max-width: 64rem; }
.mx-wi9  {  max-width: 96rem; }
.mx-wi10 {  max-width: 128rem; }

@media screen and (min-width: 48em) {
  .mx-wi1-ns  {    max-width: 1rem; }
  .mx-wi2-ns  {    max-width: 2rem; }
  .mx-wi3-ns  {    max-width: 4rem; }
  .mx-wi4-ns  {    max-width: 8rem; }
  .mx-wi5-ns  {    max-width: 16rem; }
  .mx-wi6-ns  {    max-width: 32rem; }
  .mx-wi7-ns  {    max-width: 48rem; }
  .mx-wi8-ns  {    max-width: 64rem; }
  .mx-wi9-ns  {    max-width: 96rem; }
  .mx-wi10-ns {    max-width: 128rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .mx-wi1-m  {    max-width: 1rem; }
  .mx-wi2-m  {    max-width: 2rem; }
  .mx-wi3-m  {    max-width: 4rem; }
  .mx-wi4-m  {    max-width: 8rem; }
  .mx-wi5-m  {    max-width: 16rem; }
  .mx-wi6-m  {    max-width: 32rem; }
  .mx-wi7-m  {    max-width: 48rem; }
  .mx-wi8-m  {    max-width: 64rem; }
  .mx-wi9-m  {    max-width: 96rem; }
  .mx-wi10-m {    max-width: 128rem; }
}

@media screen and (min-width: 64em)  {
  .mx-wi1-l  {    max-width: 1rem; }
  .mx-wi2-l  {    max-width: 2rem; }
  .mx-wi3-l  {    max-width: 4rem; }
  .mx-wi4-l  {    max-width: 8rem; }
  .mx-wi5-l  {    max-width: 16rem; }
  .mx-wi6-l  {    max-width: 32rem; }
  .mx-wi7-l  {    max-width: 48rem; }
  .mx-wi8-l  {    max-width: 64rem; }
  .mx-wi9-l  {    max-width: 96rem; }
  .mx-wi10-l {    max-width: 128rem; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

