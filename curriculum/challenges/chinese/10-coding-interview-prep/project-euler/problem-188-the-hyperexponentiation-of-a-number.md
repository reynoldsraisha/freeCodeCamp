---
id: 5900f4291000cf542c50ff3b
title: 问题188：数字的过度扩展
challengeType: 5
videoUrl: ''
---

# --description--

由↑^ b或ba表示的正整数b的数字a的过度增强或分解通过以下方式递归地定义：a↑↑1 = a，a↑↑（k + 1）= a（a↑↑k ）。

因此我们有例如3↑↑2 = 33 = 27，因此3↑↑3 = 327 = 7625597484987和3↑↑4大致是103.6383346400240996 \* 10 ^ 12。查找1777↑↑1855的最后8位数字。

# --hints--

`euler188()`应该返回95962097。

```js
assert.strictEqual(euler188(), 95962097);
```

# --solutions--

