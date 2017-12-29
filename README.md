## 瀑布流新闻网站
[预览地址](https://kotou.github.io/waterfall-sinanews/index.html)
## 懒加载原理
在页面载入的时候将页面上的img标签的src设置为空或同一个小图片，把真实地址存放在一个自定义属性中，如data-src来存放真实图片地址，通过js判断图片是否出现在窗口视野中，当图片出现在视野中时将data-src存放的真实地址放到出现的图片的src上。、
## 瀑布流原理
先通过计算出一排能够容纳几列元素，然后寻找各列之中所有元素高度之和的最小者，并将新的元素添加到该列上，一行排满后下一行继续寻找所有列的各元素之和的最小者，继续添加至该列上，如此循环下去，直至所有元素均能够按要求排列为止。
