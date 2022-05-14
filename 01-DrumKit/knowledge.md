# CSS
## 长度单位
比起使用（pt, cm, mm, in, pc）等绝对单位，编写网页时更推荐使用相对性单位，例如（em, px, rem）。

- px：px是CSS的魔法单位，被认定为小但仍可见，并且水平向的1px宽的线可以清晰地显示出来的单位。因此px不是一个不变的距离，它根据装置种类及其使用方法有所不同，去除了那你知道装置解析度的需要。
- em：在font-size中使用是相对于父元素的字体大小，在其他属性中使用是相对于自身的字体大小
- rem：rem（em的根）是文件的根元素的字体大小。与在每个元素里都可能不一样的em不同，rem在整份文件中都是一致的。例如，若要给p以及h1元素一样的左边距，可比较以下两张样式表写法。
旧版本
- vh：视窗高度的1%
- vw：视窗宽度的1%

```CSS
p { margin-left: 1em; }
h1 { font-size: 3em; margin-left: 0.333em; }
```
新版本
```CSS
p { margin-left: 1rem; }
h1 { font-size: 3em; margin-left: 1rem; }
```

## flex 布局
flex弹性盒模型有三个版本：
- box（旧版本，2009 W3C）：`display: box | inline-box;`
- flexbox（混合版本）：`display: flexbox | inline-flexbox;`
- flex（新版本）：`display: flex | inline-flex;`

包含6个属性：
- flex-direction
- flex-wrap
- *flex-flow*
- justify-content（主轴上的对齐方式）
    - flex-start
    - flex-end
    - center
    - space-between
    - space-around
- align-items（交叉轴上的对齐方式）
    - flex-start
    - flex-end
    - center
    - baseline
    - stretch
- align-content

## 模板字符串
## CSS选择器，JS选择器（原生）
## 触发事件e
## audio.play(), audio.currentTime
## Array.from()
## Array.forEach();

**参考**
- https://www.w3.org/Style/Examples/007/units.zh_CN.html
- https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html
- https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Building_blocks/Values_and_units