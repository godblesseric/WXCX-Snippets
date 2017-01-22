# 微信小程序 snippets for vscode

### 触发命令：**wx**
### 组成
| snippet | 对应 |
| -----|----:|
| cx_json.json | [框架](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/MINA.html) |
| cx_js.json   | [组件](https://mp.weixin.qq.com/debug/wxadoc/dev/component/) |
| cx_wxml.json   | [API](https://mp.weixin.qq.com/debug/wxadoc/dev/api/) |
| canvas.json | [canvas 教程](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API/Tutorial) |

### ㊟ 关于canvas

+ 触发命令：**cvs**
+ 包含了 canvas API 的全部 snippet，所以你也可以把它用在web项目中

小程序canvas方法与canvas API对应关系，没有特别对应直接使用canvas API

| 小程序 canvas | canvas API |
| -----|----:|
| wx-createCanvasContext | cvs-getContext |
| wx-canvasToTempFilePath | cvs-toDataURL |
| wx-createCircularGradient | cvs-createRadialGradient |
| wx-setFillStyle | cvs-fillStyle *** |
| wx-setStrokeStyle | cvs-strokeStyle *** |
| wx-setShadow | cvs-shadowOffsetX *** |
| wx-setLineWidth | cvs-lineWidth |
| wx-setLineCap | cvs-lineCap |
| wx-setLineJoin | cvs-lineJoin |
| wx-setMiterLimit | cvs-miterLimit |
| wx-setFontSize | cvs-font |
| wx-setGlobalAlpha | cvs-globalAlpha |
| wx-draw | 无 |

