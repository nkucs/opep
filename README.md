# 1. Issue 规范

> 请详细阅读以下内容之后再发布Issue❗❗❗

- 不要发无意义的Issue

- 请在合适的项目下发布Issue
  - 需求相关发布在<https://github.com/nkucs/opep/issues>
  - 后端,数据库,API 相关发布在 <https://github.com/nkucs/server/issues> 
  - 前端-学生端相关发布在<https://github.com/nkucs/student-frontend/issues>
  - 前端-教师端相关发布在<https://github.com/nkucs/teacher-frontend/issues>
  - 前端-管理员端相关发布在<https://github.com/nkucs/admin-frontend/issues>

- 请确定 Issue 的类型
- 标题请遵守模板的形式
- 为Issue加上合适的标签(参见下述标签分类)
- 可以@相关team



## 1.1 技术/需求/数据库/API 相关Issue规范

### 标题规范

##### 标题模板:

{Issue类型}[处理状态]  Issue的具体描述

Issue类型:

- 技术
- 需求
- 数据库
- API
- 环境配置

##### 处理状态:

- 待确认: 默认状态
- 已确认: 相关负责人员确认之后更改为已确认状态
- 处理中: 将Issue分配到具体负责人后更改为处理中状态 
- 已解决: 负责人解决该Issue更改为已解决状态

例如:

`{数据库}[待确认] User表中age的字段类型错误`

`{API}[已确认] 获取所有课程API中缺少id字段`

`{环境配置}[已确认]在Windows下无法安装某个package `

`{技术}[已确认]用户刷新页面之后会退出登录状态`

### 标签分类

TODO: 待补充具体标签

### 内容规范

1. 请尽量详细描述出具体问题

   如果API/技术文档有问题, 请附带具体链接, 如[https://github.com/nkucs/opep/wiki/%E6%95%B0%E6%8D%AE%E5%BA%93%E6%96%87%E6%A1%A3#student-%E5%AD%A6%E7%94%9F%E8%A1%A8](https://github.com/nkucs/opep/wiki/数据库文档#student-学生表)

2. 请描述出现问题时所在的环境

   例如: Windows 10, Python 3.6 , Django版本2.1  (当然请尽量在统一的环境下开发)

3. 如果可能的话, 请附带截图或者错误信息

## 1.2 开发任务相关Issue规范

### 标题规范

##### 标题模板:

\{开发}[总体模块]\[具体模块][组长名] 具体开发任务的描述

例如: 

`{开发}[课程模块][实验课管理](小明) 实现获取某个课程所有实验课的API`

### 分类标签

TODO: 待补充具体标签

### 内容规范

请尽量清晰的表达出你们的具体任务

