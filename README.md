![LOGO](http://white.oneplus.xin/img/Van.png)
[![AstrBot](https://img.shields.io/badge/AstrBot-Plugin-purple?style=flat-square)](https://github.com/Soulter/AstrBot)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](./LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-orange?style=flat-square)]()
# **Van词库** 
*~~适配NoneBot的Python词库~~*<br/><br/>
**适配*AstrBot*的Python词库**<br/>
## 🔧 **适配说明**

### **主要改动：**

1. **事件处理**：
  - [x] - 使用 `@filter.event_message_type` 替代 NoneBot 的 `on_message`
  - [x] - 使用 `AstrMessageEvent` 替代 `GroupMessageEvent/PrivateMessageEvent`

2. **消息组件**：
  - [x] - 使用 `MessageChain` 和 `Plain`, `Image`, `At` 等组件
  - [x] - 支持 AstrBot 的统一消息模型

3. **配置系统**：
  - [x] - 使用 AstrBot 的配置系统 (`_conf_schema.json`)
  - [x]- 配置可在 WebUI 中可视化修改

4. **指令系统**：
   - [x]- 支持 AstrBot 的指令组系统
   - [x]- 保持原有的管理员指令兼容性

5. **权限管理**：
  - [x] - 使用 `@filter.permission_type(filter.PermissionType.ADMIN)`
  - [x] - 同时支持配置中的管理员列表

### **平台兼容性：**
- [x] - QQ 个人号（OneBot v11）
- [x] - QQ 官方机器人
- [ ] -支持AstrBot其他平台
### **保留的功能：**
- 所有关键词匹配模式
- 变量替换系统
- 特殊语法处理
- 媒体消息支持
- 冷却时间控制
- 词库管理功能

## 感谢Van词库作者ZiYi对词库移植至AstrBot所给予的支持！
[回到顶部](#van词库)
