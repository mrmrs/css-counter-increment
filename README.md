# css-counter-increment 1.0.6

Css module of single purpose classes for counter increment

#### Stats

214 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-counter-increment
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-counter-increment
```

ssh:
```
git clone git@github.com:tachyons-css/css-counter-increment.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-counter-increment";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-counter-increment@1.0.6/css/css-counter-increment.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-counter-increment">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COUNTER INCREMENT
*/
.ci-plus { counter-increment: count; }
.ci-minus { counter-increment: count -1; }
.ci-none { counter-increment: none; }
.ci-i { counter-increment: inherit; }
@media screen and (min-width: 48em) {
 .ci-plus-ns { counter-increment: count; }
 .ci-minus-ns { counter-increment: count -1; }
 .ci-none-ns { counter-increment: none; }
 .ci-i-ns { counter-increment: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ci-plus-m { counter-increment: count; }
 .ci-minus-m { counter-increment: count -1; }
 .ci-none-m { counter-increment: none; }
 .ci-i-m { counter-increment: inherit; }
}
@media screen and (min-width: 64em) {
 .ci-plus-l { counter-increment: count; }
 .ci-minus-l { counter-increment: count -1; }
 .ci-none-l { counter-increment: none; }
 .ci-i-l { counter-increment: inherit; }
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

ISC

