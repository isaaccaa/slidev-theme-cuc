# slidev-theme-CUC

[![NPM version](https://img.shields.io/npm/v/slidev-theme-cuc?color=3AB9D4&label=)](https://www.npmjs.com/package/slidev-theme-cuc)

A (...) theme for [Slidev](https://github.com/slidevjs/slidev).

[Live Demo](https://slidev-theme-cuc.netlify.app)
<!--
  Learn more about how to write a theme:
  https://sli.dev/themes/write-a-theme.html
--->

<!--
  run `npm run dev` to check out the slides for more details of how to start writing a theme
-->

<!--
  Put some screenshots here to demonstrate your theme

  Live demo: [...]
-->

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>CUC</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/themes/use).

## Layouts

This theme provides the following layouts:

### cover

![cover](https://gitee.com/isaaccaa/pictures/raw/master/img2022/01.png)

### default page

![about](https://gitee.com/isaaccaa/pictures/raw/master/img2022/02.png)

### imagex

```markdown
---
layout: imagex
image: https://gitee.com/isaaccaa/pictures/raw/master/img2022/0186795d843896a8012060be1cbe75.jpg
pos: center
size: h-260px
---

somgthing

---
```

![image](https://gitee.com/isaaccaa/pictures/raw/master/img2022/03.png)

## Contributing

- `npm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to generate the preview PDF
- `npm run screenshot` to generate the preview PNG
