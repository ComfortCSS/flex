# ComfortCSS Flexbox

Clean, modular, and RTL-ready Flexbox classes with zero specificity (`:where()`) and logical properties. Part of the Ultra CSS ecosystem.

## Installation

```bash
npm install @comfortcss/flex @comfortcss/tokens
```

Requires `@comfortcss/tokens` for spacing values (peer dependency).

## Usage

```css
@import '~@comfortcss/tokens';
@import '~@comfortcss/flex';
```

## Container

| Classes | Purpose |
|---------|---------|
| `.flex`, `.inline-flex` | Create flex container |

## Direction

| Classes | Purpose |
|---------|---------|
| `.flex-row`, `.flex-col`, `.flex-row-reverse`, `.flex-col-reverse` | Create flex container |

## Wrap

| Classes | Purpose |
|---------|---------|
| `.flex-wrap`, `.flex-nowrap`, `.flex-wrap-reverse` | Line wrapping |

## Main axis

| Classes | Purpose |
|---------|---------|
| `.justify-*` (start, end, center, between, around, evenly) | Horizontal alignment |

## Cross axis

| Classes | Purpose |
|---------|---------|
| `.items-*`, `.content-*` | Vertical alignment |

## Items

| Classes | Purpose |
|---------|---------|
| `.flex-1`, `.flex-auto`, `.flex-none`, `.grow`, `.shrink`, `.basis-*` | Item sizing & flexibility |

## Gap

| Classes | Purpose |
|---------|---------|
| `.gap-*`, `.gap-x-*`, `.gap-y-*` (size from tokens) | Spacing between items |

## Dependencies

- [`@comfortcss/tokens`](https://github.com/ComfortCSS/tokens)

## License

[MIT](LICENSE)
