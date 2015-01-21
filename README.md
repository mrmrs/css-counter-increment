# CSS COUNTER INCREMENT

  Mobile-first classes for css-counter-increment.
  Set the desired css-counter-increment on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-counter-increment
```
View on [npm](https://www.npmjs.org/package/css-counter-increment)


## File Size

881B counter-increment.css
698B counter-increment.min.css
184B minified and gzipped

## The Code
```
.ci-plus {  counter-increment: count; }
.ci-minus { counter-increment: count -1; }
.ci-none {  counter-increment: none; }
.ci-i {     counter-increment: inherit; }

@media screen and (min-width: 48em) {
  .ci-plus-ns {  counter-increment: count; }
  .ci-minus-ns { counter-increment: count -1; }
  .ci-none-ns {  counter-increment: none; }
  .ci-i-ns {     counter-increment: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ci-plus-m {  counter-increment: count; }
  .ci-minus-m { counter-increment: count -1; }
  .ci-none-m {  counter-increment: none; }
  .ci-i-m {     counter-increment: inherit; }
}

@media screen and (min-width: 64em)  {
  .ci-plus-l {  counter-increment: count; }
  .ci-minus-l { counter-increment: count -1; }
  .ci-none-l {  counter-increment: none; }
  .ci-i-l {     counter-increment: inherit; }
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

