# picture-watermark 图片水印
## 简介
这是一个专门用于给身份证、驾照等敏感证件打水印的工具，完全基于浏览器本地 API，无任何网络请求。
## 原理
使用浏览器 HTML5 的 `canvas` 功能，对 `canvas` 使用 `fillText()` 方法来填充水印。
![demo.jpg](images/demo.jpg)

## 功能
- 批量添加水印。
- 完全本地，不依赖网络。
- 无其他框架依赖，单 HTML 文件，使用原生 JavaScript。
- 批量下载水印图片。
- 支持设置水印颜色、透明度、字体大小。
- （新增）支持水印角度自定义。
- （新增）支持调整水印水平、垂直间距。
- （新增）支持字体选择。
- （新增）导出支持选择格式和质量。
## 使用
直接下载 `watermark.html` 在本地浏览器打开。
## 贡献
如果你想参与这个软件的开发，欢迎 PR。