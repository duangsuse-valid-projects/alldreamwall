# AllDreamWall ![Based On MDUI](https://img.shields.io/badge/HTML_UI_Framework-MDUI-pink.svg?style=flat-square) ![By duangsuse](https://img.shields.io/badge/author-duangsuse-green.svg?style=flat-square) ![It's a client](https://img.shields.io/badge/type-client-red.svg?style=flat-square)

一个基于 MDUI 的 [傲梦](https://all-dream.com) 分享平台 [客户端](https://duangsuse.github.io/alldreamwall/all_dream.html)，纯 __HTML + CSS + JavaScript__ 编写

## 特性 | Features

+ 基本前端配置：已经填写 OpenGraph 标签，含 `favicon` 和 `title`，UA 兼容性，`viewport`、`theme-color`、基于回调函数的异步等
+ 质感设计：基于 MDUI 开发，支持主题和自动夜间模式（可以读取和自定义 `localStorage` 中的 `dark`、`nightBegin`、`nightEnd`）
+ 瀑布流：基于 Masonry 的自动作品瀑布流，但不支持自动翻页
+ 查看分类：支持几乎所有官方前端支持的模式： __全部、MindMap、Scratch、JS Turtle、推荐__
+ 分页：支持选择每页项目数，默认 25 条，支持撤销
+ 翻页：支持向前/向后
+ 包含取自 __mafintosh/json-markup__ 并完善的格式化代码，修改得到质感配色且支持自动 13 十进制位 number `Date` 注释
+ 查看比官方客户端更多的信息，日期格式化，项目总数统计数据
+ 查看 __用户、分享、宝石/金币榜、分享列表、分享消息__ 的裸 JSON 数据
+ 下载文件和 JSON 裸数据（基于 download.js）
+ 快捷键，`Enter` for refresh，`<-/->` decreast/increase page no., `m` for count menu, `t` for rows per page, `c` for categories menu
+ 支持生成官方前端项目链接

## 用到的库 | Used libraries

+ 界面，MDUI https://mdui.org
+ JSON prettyprint，json-markup https://github.com/mafintosh/json-markup
+ 瀑布流布局，Masonry https://unpkg.com/masonry-layout@4/dist/masonry.pkgd.min.js
+ 下载文本数据，download.js https://cdnjs.loli.net/ajax/libs/downloadjs/1.4.8/download.js

## 许可证 | License

alldreamwall.html: __GNU LGPL 3.0，其中包含引用其它授权的代码不包含在内__

## 截图 | Shots

![0](https://github.com/duangsuse/alldreamwall/raw/master/Screenshot_20180718_204626.png)
![1](https://raw.githubusercontent.com/duangsuse/alldreamwall/master/Screenshot_20180718_223457.png)
![2](https://raw.githubusercontent.com/duangsuse/alldreamwall/master/Screenshot_20180718_223512.png)
![3](https://raw.githubusercontent.com/duangsuse/alldreamwall/master/Screenshot_20180718_223600.png)
