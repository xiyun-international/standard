# 浏览器兼容规范

目前，我们只需要兼容现代浏览器，如：Chrome、以及国产双核浏览器（360、QQ）。
所以你需要在 HTML 中，加入 META 标签
```html
<meta name="renderer" content="webkit">
<meta http-equiv="X-UA-Compatible" content="IE=edge,Chrome=1">
```
