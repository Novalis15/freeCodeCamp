---
id: 5a90376038fddaf9a66b5d3c
title: 使用 justify-items 水平对齐所有项目
challengeType: 0
videoUrl: 'https://scrimba.com/p/pByETK/cJbpECn'
forumTopicId: 301120
---

# --description--

有时你想让 CSS 网格中的网格项共享对齐方式。你可以像之前学习的那样分别设置它们的对齐方式，也可以对网格容器使用 `justify-items` 使它们一次性沿水平轴对齐。这个属性能接受我们在之前两个挑战中学到的所有值作为属性值，但与之前不同的是，它会将网格中**所有**的网格项按所设置的方式对齐。

# --instructions--

请使用 `justify-items` 属性设置所有网格项水平居中。

# --hints--

class 为 `container` 的元素应具有 `justify-items` 属性且属性值应为 `center`。

```js
assert(
  code.match(
    /.container\s*?{[\s\S]*justify-items\s*?:\s*?center\s*?;[\s\S]*}/gi
  )
);
```

# --solutions--

