# How to add auto number marker before headings of Typora?

## How

Demo:

Demo for auto number marker of content and left side outline:

![](007S8ZIlgy1gipb1s7volj319s0u0gvv.jpg)



Demo for auto number marker of `[TOC]` :

![demo-of-outline-and-toc](demo-of-outline-and-toc.jpg)





For Typora support costomized CSS style, so we can add our theme css file.

1. open theme folder
2. add a new file name "base.user.css"

```css
/* for add heading counter*/
@import "harold/outline-head-counter.css";
@import "harold/toc-head-counter.css";
@import "harold/content-head-counter.css";
```

I add three css files to add auto number maker separately for [outline](outline-head-counter.css), [toc](toc-head-counter.css) and [content](content-head-counter.css).



3. restart Typora.app

## Reference:

- [https://support.typora.io/Auto-Numbering/](https://support.typora.io/Auto-Numbering/)
