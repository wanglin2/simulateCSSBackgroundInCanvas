# simulateCSSBackgroundInCanvas

在`canvas`中模拟`css`的`background-size`、`background-position`、`background-repeat`三个属性的部分效果。单位仅支持`px`、`%`。

## 使用

```js
import drawBackgroundImageToCanvas from './SimulateCSSBackgroundInCanvas'

let width = 500
let height = 500
let img = '/1.jpg'
let canvas = document.createElement('canvas')
canvas.width = width
canvas.height = height
drawBackgroundImageToCanvas(ctx, width, height, img, {
  backgroundRepeat: 'repeat-y',
  backgroundSize: '60%',
  backgroundPosition: 'center center'
})
```
