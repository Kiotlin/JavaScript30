# CSS
## 定位属性
- static
- relative：相对于默认位置（即static）进行偏移。
- absolute
- fixed
- sticky

## box-shadow 阴影效果
```CSS
/* x偏移量 | y偏移量 | 阴影颜色*/
box-shadow: 60px -16px black;

/* x偏移量 | y偏移量 | 阴影模糊半径 | 阴影颜色 */
box-shadow: 10px 5px 5px black;

/* x偏移量 | y偏移量 | 阴影模糊半径 | 阴影扩散半径 | 阴影颜色 */
box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);

/* 插页(阴影向内) | x偏移量 | y偏移量 | 阴影颜色 */
box-shadow: inset 5em 1em gold;

/* 任意数量的阴影之间以逗号分隔 */
box-shadow: 
    3px 3px red, 
    -1em 0 0.4em olive;
```

## transition CSS中控制属性变换速度/隐式过渡

- *transition*（简写属性）
```CSS
div {
    transition: <property> <duration> <timing-function> <delay>
}
```
- transition-property（指定哪些属性会发生过渡）
- transition-delay（发生延迟）
- transition-duration（过渡时长）
- transition-timing-function（过渡动画指定）

## transform-origin 改变元素变形时的原点
left | 0%
center | 50%
right | 100%
top | 0%
bottom | 100%