---
title: WebSave 支持与反馈
permalink: /support
---

# WebSave 支持与反馈

WebSave 0.1 处于免费内测阶段。遇到问题或希望参与内测，请发送邮件至 [saixialv@gmail.com](mailto:saixialv@gmail.com)。

## 反馈时建议提供

- WebSave 版本号与 Chrome 版本。
- 使用本地文件夹还是 WebDAV。
- 可复现问题的操作步骤和错误提示。
- 已移除私人内容的截图，或由你确认后手动发送的诊断 JSON。

请不要发送 WebDAV 密码、访问令牌、验证码、私人网页正文、真实 NAS 地址、完整浏览历史或未经处理的完整日志。

## 常见问题

### 密码会同步到 Google 吗？

不会。开启“在此设备记住密码”时，密码只保存在当前设备的 Chrome 扩展本地存储中，不使用 Chrome Sync，也不会出现在配置导出文件里。

### 为什么重启 Chrome 后需要重新输入密码？

当“在此设备记住密码”关闭时，密码只在当前 Chrome 会话内有效。重新开启该选项并保存配置后，密码可在当前设备跨 Chrome 重启使用。

### WebSave 会把网页上传给开发者吗？

不会。内容只写入你选择的本地文件夹，或发送到你配置的 WebDAV 地址。

### 如何删除数据？

可在 WebSave 设置中重置配置或清除扩展数据；已经保存到本地文件夹或 WebDAV 的文件需在相应存储中删除。

- [返回 WebSave 首页](README.md)
- [查看隐私政策](privacy.md)
