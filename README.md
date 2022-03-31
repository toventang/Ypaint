# Ypaint

## 使用方法

`import paint from 'Ypaint'`
`const newPaint = new Paint(paint);`

## 方法参数

### 绘制矩形：
```
newPaint.init({
    drawWay: 'rectangle',
    lineWidth: 4, 
    color: 'red',
    radius: 2,
    rectangleType: 'stroke'
})
```

### 画笔工具：
```
newPaint.init({
    drawWay: 'pencil',
    lineWidth: 4, 
    color: 'red',
});
```

### 绘制箭头：
```
newPaint.init({
    drawWay: 'arrow',
    lineWidth: 4, 
    color: 'red',
})
```

### 绘制圆形：
```
newPaint.init({
    drawWay: 'circel',
    lineWidth: 4, 
    color: 'red', 
    fillColor: 'blue'
});
```


