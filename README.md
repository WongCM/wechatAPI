# 微信 API - 强大的微信接口和 Hook 工具

## 🌟 项目简介
微信黑科技项目基于微信Windows协议和安卓协议开发，提供了一套强大的微信 API工具。我们的目标是通过兼容微信协议，为用户提供更开放和可定制的微信接入能力。

**试用申请自动通过，邮件标题请设置为：WechatApi申请试用-个人版、WechatApi申请试用-商业版，邮箱及邮件模板详见下方**

## ✨ 特色功能
- **原生接口**：对微信原生接口的直接封装。
- **二开接口**：基于原生接口的扩展，实现更多功能。
- **多开支持**：支持多开微信。
- **视频号**：融合安卓版本[视频号API](doc/视频号)。
- **朋友圈**：融合安卓版本[朋友圈API](doc/朋友圈)。
- **直播间**：融合安卓版本[直播间API](doc/直播间)。
- **丰富的API**：融合安卓和Windows版微信的API为一体 [点击查看API](menu.md)

## 🚀 快速启动
请参考我们的 [快速启动指南](doc/快速启动.md) 和 [API接口文档](menu.md) 以快速开始使用微信 API。

## 🔧 使用必要条件
- 设备要求：实体 Windows 电脑 Win7 以上系统 或 云服务器 Windows 电脑 Win7 以上系统。
- 微信版本要求：3.9.5.* 或 3.9.2.*（该版本会缺失一些api，建议使用3.9.5.*）

## 🆓 免费和付费版本
- **免费版本**：
  - 白嫖：成功破解付费版本提出可行性方案，奖金丰厚。
  - 试用：
    - 个人用户：支持单微信免费试用7天。
    - 企业用户：支持单设备免费试用14天。
  - 合作：
    - 开发者：开发基于该软件的工具产品，获得设备永久使用权及额外奖金。
    - 推广员：推广软件，享受优惠采购和奖金。
- **付费版本**：
  - ~~微信版：限制微信号，不限设备数量。（可换绑微信）~~（为减少维护成本，暂时不开放限制微信版）
  - 设备版：限制设备，不限微信数量。（可换绑设备）
  - 无限版：不限微信和设备数量。（为规范市场，个人暂时不支持购买）

## 📞 支持和服务
- **缺少某些微信API**：免费开发。
- **业务功能定制**：可洽谈。
- **新版本升级**：
  - 个人用户：大版本升级付费20%，小版本免费升级。
  - 企业用户：根据是否有定制功能决定升级费用。
- **维护**：全职维护团队。
- **账号安全**：历史上没有因为软件封过号，懂技术应该了解封号大都是调用频率、内容原因。
- **换绑设备/微信**：每月固定时间批量换绑，如需要换绑请发邮件。

## 📬 联系方式
- 商务咨询：wetool_api@163.com
- 试用咨询：wetool_api@163.com
- **邮件格式**：
  - **试用申请自动通过，务必将*[邮件标题]()*设置为以下其一，务必留联系方式**：
    - WechatApi申请试用-个人版
    - WechatApi申请试用-商业版
```
  标题：[目的xxxx]
  正文：
  - 计划采购版本及数量:
    - xxxxx
  - 联系方式如下:
    - QQ: xxxxx
    - 微信: xxxxx
    - 电话: xxxxx
    - Telegram: xxxxx
    - WeChat: xxxxx
```


## 🤝 贡献和反馈
我们欢迎并鼓励社区贡献和反馈。如果您有任何建议或想要贡献代码，请通过 Issues 或 Pull Requests 与我们联系。

## 🌐 社交媒体和社区
QQ群：616651311 （仅技术支持，无需求不要加！）

## 🔖 标签
`微信` `API` `Hook` `微信开发` `协议兼容` `多开微信`

## 📅 更新日志
### 2024年
- **1月03日**：
  - 准备发朋友圈接口xml示例
  - 准备发送小程序xml示例
### 2023年
- **12月23日**：
  - 后续不再持续支持3.9.2.*版本的新api。现有api将持续支持，有bug会修复。
  - 修复[视频号作品解密](doc/视频号/视频号作品解密.md)
  - 新增[发送视频.md](doc/发送消息/发送视频.md)
  - 新增[发送链接.md](doc/发送消息/发送链接.md)
- **12月18日**：
  - 视频号私信、自动发视频号功能测试中
- **11月24日**：
  - [获取用户信息](doc/通讯录/获取用户信息.md)接口新增字段，支持通过群聊获取用户信息。
  - 新增[添加群成员到通讯录](doc/群管理/添加群成员到通讯录.md)接口。
  - 新增[WebSocket处理器](doc/处理消息/WebSocket处理器.md)
  - 新增[获取消息处理器列表](doc/处理消息/获取消息处理器列表.md)接口。
  - 新增[退出登录](doc/登录相关/退出登录.md)接口。
  - 消息推送与主动调用格式优化。
  - 修复多线程调用时的Bug。
  - [获取个人信息](doc/个人信息/获取个人信息.md)接口优化。
- **11月11日**：
  - 退出事件监听优化。
  - 消息推送优化。
  - 新增点对点消息处理器。
  - 新增一种接口调用方式。
  - python示例代码优化。
- **9月19日**：
  - 修复发送文本消息导致微信崩溃的Bug（仅x64版本）。
- **9月18日**：
  - 铭记历史，勿忘国耻。
- **9月17日**：
  - 修改编译选项，减少对运行库的依赖。
- **9月14日**：
  - 过滤掉部分主动发送消息的推送。
  - 修复邀请加入群聊接口导致的Bug。
  - 修复x64版本在初始化登录时调用接口无返回的Bug。
  - 通过接口发送的文本消息现在会显示到微信客户端。
  - 登录事件推送优化。
  - 添加好友接口优化。
- **9月6日**：
  - 支持主动发送消息的推送。
  - 新增邀请加入群聊接口。
  - 新增群聊邀请验证接口。
- **8月28日**：
  - 修改HttpServer逻辑，解决并发调用报错。
  - 获取小程序code接口编号变更。
  - 锁定微信接口编号变更。
  - 小程序授权接口编号变更。
  - 新增操作云函数接口。
  - 新增刷新小程序会话接口。
  - 新增获取小程序使用记录接口。
  - 新增更新小程序使用记录接口。
  - 新增获取小程序信息接口。
  - 新增批量获取小程序信息接口。
  - 新增获取小程序包下载地址接口。
  - 解除虚拟机不可用限制。
- **8月15日**：
  - 修复cdn下载接口下载文件不完整的Bug。
  - 更新3.9.5.8164位版本SDK。
  - wxrpd64.dll部分逻辑更新。
- **8月10日**：
  - 修复3.9.5.81版本调用任意接口后触发微信重新登录的Bug。
  - 修复删除群成员接口无效的Bug。
  - 修复关闭群聊免打扰接口无效的Bug。
  - 修复保存收款码接口无效或引发微信崩溃的Bug。
  - 修复3.9.5.81版本部分接口调用失败的Bug。
  - 修复查询数据库接口执行错误sql后的Bug。
  - 新增小程序授权接口。
  - 新增锁定微信接口。
  - wxrpd64.dll、pyrpd已知问题修复。
- **7月20日**：
  - 开放一系列视频号相关接口。
  - 开放获取小程序code接口。
  - 尝试修复获取通讯录接口卡死的Bug。
  - 调整文档结构。
- **7月9日**：
  - 修复搜一搜接口设置的偏移无效的Bug。
  - 获取数据库信息接口优化。
  - 开放数据库备份接口。
- **7月6日**：
  - 新增注入时自动patch掉微信的检查更新。
  - 新增获取H5Key接口。
  - 优化搜一搜、获取公众号历史消息接口。
  - 新增获取数据库信息接口。
  - 新增查询数据库接口。
- **6月30日**：
  - 解决cdn下载接口报错问题。
- **6月29日**：
  - 获取用户信息接口添加remark字段。
  - 批量获取用户信息接口优化。
  - 修复http服务崩溃的Bug。
- **6月28日**：
  - 开放CDN下载接口。
  - 开放搜索用户信息接口。
  - 新增获取备份库秘钥接口。
  - 修复好友数量大于100时无法成功获取的Bug。
  - 迁移文档到本站。
- **5月27日**：
  - 撰写并发布此文档。
