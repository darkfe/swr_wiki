
mdeditor
===============

直接把 `github` 的 `issues` 用的编辑器整体样式抠了出来, 自己实现了部分功能.

目前的功能有:

1. 预览 `markdown`, `markdown` 解析由 [marked][1] 实现
2. 保留并且实现了禅模式切换.
3. 使用 [inline-attach][2]插件实现了拖拽和粘贴上传, 但未保留原生的选文件上传
4. 沿袭 github 使用了 [tipsy][3] 插件来实现小提示
5. 语法高亮由 [hightlight.js][4] 插件实现, 并且使用了该插件提供的`github.css`的高亮样式.

已知的问题:

1. 直接把 github 的 css 文件整体搬过来稍作删减, 但还是有很多不用的样式.
2. php 上传尚未测试, 但前端功能可用
3. 目前多个编辑器共存可能存在问题

[1]:https://github.com/chjj/marked
[2]:https://github.com/Rovak/InlineAttachment
[3]:https://github.com/jaz303/tipsy
[4]:https://github.com/isagalaev/highlight.js



