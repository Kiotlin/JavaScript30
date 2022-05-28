# CSS
## box-sizing

元素的属性设置为 ``box-sizing: border-box`` ，这样盒模型就会转换为怪异盒模型，盒子设置的总宽高就为盒子的宽高，我们在调整边框和内边距时，不会影响改变盒子的宽高。

## transition 中定义的属性名必须与实际定义的属性名严格对应
```CSS
.class1 {
    transition: flex 0.7 cubic-bezier(0.61, -0.19, 0.7, -0.11);
    flex-grow: 1;
}
```
这样写触发动画时并不会触发 ``flex-grow`` 属性的过渡效果，必须使用 ``flex: 1;`` 来定义。

## CSS 选择器
``.class1.class2`` 表示同时具有``class1`` 和 ``class2``。

# JavaScript
## element.classList.toggle
## Event: transitionend 