## 说明
1. laydate.js是压缩后的核心代码，laydate.dev.js是开发版的源代码。
1. need目录存放着核心css
1. skins是皮肤目录
1. 将laydate pull到你的本地后，将其存放到您js相关目录下的laydate目录，不要改动laydate的结构，否则无法正常运行。

## 简要
她基于原生JavaScript精心雕琢，兼容了包括IE6在内的所有主流浏览器。她具备优雅的内部代码，良好的性能体验，和完善的皮肤体系，并且完全开源，你可以任意获取开发版源代码，一扫某些传统日期控件的封闭与狭隘。layDate本着资源共享的开发者精神和对网页日历交互无穷的追求，延续了layui一贯的简单与易用。她遵循LGPL协议，您可以免费将她用于任何个人项目。

## 更新日志

1.1

1. layer.now(timestamp,format)支持多类型参数。timestamp支持今天的前若干天，和今天的后若干天，并且如果是一个有效的时间戳,则返回该时间戳对应的日期。如果什么都没传入，则返回当前时间日期。format为日期格式，为空时则采用默认的“-”分割。
2. 优化核心代码。
3. 分和秒的选择改成10列*6行。
4. 修复星期未居中对齐的样式问题
5. 修复在页面加载完毕事件中，调用laydate所造成的立即执行的bug
6. 皮肤包新增[墨绿]。

## 备注
[官网](http://laydate.layui.com/)、[社区](http://fly.layui.com/)