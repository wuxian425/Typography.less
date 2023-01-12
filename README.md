<h1 align="left">Typography.less</h1>

<h4 align="right">A CSS file makes the article easier to read.</h4>

## Use

Download `dist/typo.less.css` and add it to your project，then use:
```
<link href="[Path]/typo.less.css" rel="stylesheet" />
```
to import Typography.less。

## Develop

You need `Node.js`, `npm` and `Less`.
If you don't have `Less`, input `npm i -g less` to your terminal.

### Packing

Input `npm run build`, you will get:
```
> typo.less@1.0.0 build
> lessc index.less dist/typo.less.css
```
and the `typo.less.css` is in `/dist`.

###### 2023 BobYang.