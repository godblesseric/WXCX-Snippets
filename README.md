# 微信小程序 snippets for vscode

### 使用

放在/Users/用户名/.vscode/extensions/目录下

### 触发命令：**cx / weui / cvs**
### 组成
| snippet | 对应 |
| -----|----:|
| cx_json.json | [框架](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/config.html) |
| cx_js.json   | [API](https://mp.weixin.qq.com/debug/wxadoc/dev/api/) |
| cx_weui.json   | [WeUI for 小程序](https://github.com/weui/weui-wxss) |
| cx_wxml.json   | [组件](https://mp.weixin.qq.com/debug/wxadoc/dev/component/) |
| canvas.json | [canvas 教程](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API/Tutorial) |

### ㊟ 关于canvas

+ 触发命令：**cvs**
+ 包含了 canvas API 的全部 snippet，所以你也可以在web项目中使用它

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

