## **CMDraw**

> 画图命令: draw
1. 画单条线

```
draw line from (76,206) to (524,195) linecolor blue linewidth 1;
```

```
from: 起始点

to: 终点

linecolor: 线条颜色 (#0000ff 或者 blue 或者 rgb(0,0,255) 三种形式均可)

linewidth: 线条宽度
```

2. 画多条线

```
draw lines (100,100) (100,300) (400,300) (400,100) (100,100);
```

```
可以使用 linecolor 和 linewidth 属性
```


3. 画圆

```
draw circle center (800,200) radius 80 fill #00f linecolor #00f;
```

```
center: 中心
radius: 半径
fill: 填充颜色
```

4. 画矩形

```
draw rectangle center (300,200) width 400 height 200 fill #f5f5f5 linewidth 1 linecolor #00f rotate 25;
```

```
width: 宽
height: 高
rotate: 旋转角度(°)
```

5. 画多边形

```
draw polygon center (300,200) radius 80 sides 5 concavity 0.5 rotate 25 fill #00f linecolor #00f;
```

```
sides: 边数
concavity： 凹度（范围 0 ~ 1）
```


5. 画文字

```
draw text center (830,420) text 不听话 size 30 linecolor blue fill red font 等线;
```

```
text: 文字
size： 文字大小
font: 字体
```

6. 画部分圆

```
draw slice center (400,400) radius 80 start 0 end 90 fill blue linecolor blue;
```

```
start: 开始度数(°)
end： 结束度数(°)
```

---

