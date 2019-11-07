# Git Commit Message 提交方案

在提交修改信息的过程中，常常不清楚应该如何进行信息描述。

一些项目中，看到相关的提版描述，不够清楚明白，不知道是新增了功能，还是
修复了 Bug 还是修补了程序中的漏洞（有安全问题），为了能规范的提交过程
中的描述，可以方便的看出本次提交的具体内容。

提交信息，主要使用了
[gitemoji](https://github.com/carloscuesta/gitmoji) 描述一些问题，也可
以不使用，只是进行简单的描述。

``` markdown
#{ type } { 提交描述 }

#{ body } { 修改具体内容 }

# :tada: 初始化项目
# :sparkles: 新特性
# :bug: 修改问题
# :pencil: 编写文档
# :art: 调整代码格式和样式
# :recycle: 重构代码
# :white_check_mark: 更新测试
# :lipstick: 更新 UI 和样式文件
# :children_crossing: 改善用户体验
# :loud_sound: 增加日志
# :mute: 移除日志
# :ok_hand: 代码审查通过
# :bento: 新增或修改资源
# :page_facing_up: 新增或者修改许可
# :construction_woker: 新增 CI 系统
# :heavy_plus_sign: 新增依赖
# :heavy_minux_sign: 移除依赖
# :arrow_down: 依赖降级
# :arrow_up: 依赖升级
# :bookmark: 发布版本标签
# :ambulance: 紧急修复
# :zap: 提升性能
# :hole: 修复漏洞问题
```
