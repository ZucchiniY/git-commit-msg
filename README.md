# Git Commit Message 提交方案

在提交修改信息的过程中，常常不清楚应该如何进行信息描述。

一些项目中，看到相关的提版描述，不够清楚明白，不知道是新增了功能，还是
修复了 Bug 还是修补了程序中的漏洞（有安全问题），为了能规范的提交过程
中的描述，可以方便的看出本次提交的具体内容。

提交信息，主要使用了
[gitemoji](https://github.com/carloscuesta/gitmoji) 描述一些问题，也可
以不使用，只是进行简单的描述。

将项目下的 *.stCommitMsg* 文件放到 *commit.template* 定义的路径下，可
以使用命令 `git config commit.template` 进行查询，然后将内容写入的项目
中即可。

具体的内容是按照 .stCommitMsg 中的信息进行编写。需要写清楚，是更新还是
修复问题，修复的哪个问题，涉及了哪些文件（包括增加、删除、修改），然后
描述一下为什么要这样改，如果是依据 issue 或者是 bug 则要说明是哪些。

| 内容               | 使用的 emoji           |
|:-------------------|:-----------------------|
| 初始化项目         | `:tada:`               |
| 新特性             | `:sparkles:`           |
| 修改问题           | `:bug:`                |
| 编写文档           | `:pencil:`             |
| 调整代码格式和样式 | `:art:`                |
| 重构代码           | `:recycle:`            |
| 更新测试           | `:white_check_mark:`   |
| 更新 UI 和样式文件 | `:lipstick:`           |
| 改善用户体验       | `:children_crossing:`  |
| 增加日志           | `:loud_sound:`         |
| 移除日志           | `:mute:`               |
| 代码审查通过       | `:ok_hand:`            |
| 新增或修改资源     | `:bento:`              |
| 新增或者修改许可   | `:page_facing_up:`     |
| 新增 CI 系统       | `:construction_woker:` |
| 新增依赖           | `:heavy_plus_sign:`    |
| 移除依赖           | `:heavy_minux_sign:`   |
| 依赖降级           | `:arrow_down:`         |
| 依赖升级           | `:arrow_up:`           |
| 发布版本标签       | `:bookmark:`           |
| 紧急修复           | `:ambulance:`          |
| 提升性能           | `:zap:`                |
| 修复漏洞问题       | `:hole:`               |
