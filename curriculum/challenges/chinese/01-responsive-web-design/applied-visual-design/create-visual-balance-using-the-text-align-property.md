---
id: 587d7791367417b2b2512ab3
title: 使用 text-align 属性创建视觉平衡
challengeType: 0
videoUrl: 'https://scrimba.com/c/c3b4EAp'
forumTopicId: 301053
---

# --description--

这部分课程的主题是应用视觉设计。开始的挑战基于美化一个卡片组件的外观，借此展示了若干核心原则。

web 内容大部分都是文本。CSS 里面的 `text-align` 属性可以控制文本的对齐方式。

`text-align: justify;` 可以让除最后一行之外的文字两端对齐，即每行的左右两端都紧贴行的边缘。

`text-align: center;` 可以让文本居中对齐。

`text-align: right;` 可以让文本右对齐。

`text-align: left;` 是 `text-align` 的默认值，它可以让文本左对齐。

# --instructions--

请让内容文本为 `"Google"` 的 `h4` 标签居中对齐；让介绍了 Google 创立历程的段落文本两端对齐。

# --hints--

应在 `h4` 标签上使用 text-align 属性设置文本居中对齐。

```js
assert($('h4').css('text-align') == 'center');
```

应在 `p` 标签上使用 text-align 属性设置文本两端对齐。

```js
assert($('p').css('text-align') == 'justify');
```

# --solutions--

