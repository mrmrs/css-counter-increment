# css-counter-increment

Functional CSS for counter-increment

## Filesize

| File | Size |
|------|------|
| `dist/counter-increment.css` | 889 bytes |
| `dist/counter-increment.min.css` | 659 bytes (171 Gzipped) |

## Install

```sh
npm install css-counter-increment
```

## Usage

### Import

```css
@import "css-counter-increment";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-counter-increment/dist/counter-increment.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-counter-increment/dist/counter-increment.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ci-plus` | `counter-increment: count;` |
| `.ci-minus` | `counter-increment: count -1;` |
| `.ci-none` | `counter-increment: none;` |
| `.ci-i` | `counter-increment: inherit;` |
| `.ci-plus-s` | `counter-increment: count;` |
| `.ci-minus-s` | `counter-increment: count -1;` |
| `.ci-none-s` | `counter-increment: none;` |
| `.ci-i-s` | `counter-increment: inherit;` |
| `.ci-plus-m` | `counter-increment: count;` |
| `.ci-minus-m` | `counter-increment: count -1;` |
| `.ci-none-m` | `counter-increment: none;` |
| `.ci-i-m` | `counter-increment: inherit;` |
| `.ci-plus-l` | `counter-increment: count;` |
| `.ci-minus-l` | `counter-increment: count -1;` |
| `.ci-none-l` | `counter-increment: none;` |
| `.ci-i-l` | `counter-increment: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ci-plus-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/counter-increment.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/counter-increment.css` — formatted
- `dist/counter-increment.min.css` — minified

## License

MIT
