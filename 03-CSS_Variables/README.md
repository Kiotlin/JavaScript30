# CSS
## 伪类:root, CSS变量
`:root` 这个 CSS 伪类匹配文档树的根元素。对于 HTML 来说，`:root` 表示 <html> 元素，除了优先级更高之外，与 html 选择器相同。

CSS变量与color，font-size等正式属性没有什么不同，只是没有默认的含义，所以CSS变量（CSS Variables）又称为“CSS自定义属性”。声明CSS变量时，需要在变量名前加`--`。
各种值都可以放入CSS变量， `var()`函数用于读取变量，第二个参数是默认值。CSS变量值只能作为属性值，不能用作属性名：
```CSS
:root {
    --base: #ffc600;
    --spacing: 10px;
    --blur: 10px;
}

.hl {
    color: var(--base);
    padding: var(--spacing, 10px 15px 20px);
}
```

## filter
filter将模糊或颜色偏移等图片效果应用于元素上。常用于调整图像，背景和边框的渲染。

# JS
## 回调函数的this
## Event 'mousemove'
监测当指针设备（通常指鼠标）在元素上移动时，mousemove事件被触发。