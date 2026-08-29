# ColorOS 便签分享水印

> 模块包名：`com.jy.notewatermark`  
> 推荐作用域：ColorOS 便签（`com.coloros.note`）

去掉或快速自定义 ColorOS 便签分享长图底部的「ColorOS 便签」水印。

## 功能

- 直接在模块设置页输入并保存自定义水印
- 一键清空水印
- 空水印时可保留原水印区域作为约两行高的底部留白
- 可关闭留白并完全折叠水印区域
- 不修改笔记正文，不向原笔记写入换行
- 兼容旧版 `watermark.txt` 配置

## 使用方法

1. 安装模块。
2. 在 LSPosed、vector 或其他兼容 LSPosed API 的框架中启用模块。
3. 将 ColorOS 便签（`com.coloros.note`）加入作用域。
4. 点击桌面或应用列表中的「便签分享水印」，设置水印文字与底部留白。
5. 冷启动便签，再将笔记分享或保存为图片。

## 兼容性

- 已核验：ColorOS 16.0.10、便签 16.6.22、Android 16
- 最低 Android 8.0（API 26）
- 纯 Java/Xposed 模块，不包含 native `.so`；单个 APK 支持所有 CPU 架构

便签升级后内部接口可能变化；如遇失效，请携带便签版本号反馈。

## 源码与反馈

- 源码：[araea/note-watermark](https://github.com/araea/note-watermark)
- 问题反馈：[GitHub Issues](https://github.com/araea/note-watermark/issues)
- QQ 群：956758505

本模块采用 Apache-2.0 或 MIT 双许可证发布。
