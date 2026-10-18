# 墨澜创作台 · Molan Creative Studio

**让正文、人物设定与 AI 创作任务回到同一张书桌。**

面向中文小说作者的 Windows 桌面创作工作台，现开放 **0.1.6 试用版**下载，欢迎用真实写作需求参与打磨。

[**下载 Windows 安装程序**](https://github.com/CX0072/molan-desktop/releases/download/v0.1.6/MolanCreativeStudio_Setup_0.1.6_Windows_x64.exe) · [**下载完整压缩安装包**](https://github.com/CX0072/molan-desktop/releases/download/v0.1.6/MolanCreativeStudio_0.1.6_Windows_x64.zip) · [所有发行版与更新记录](https://github.com/CX0072/molan-desktop/releases) · [提交建议或问题](https://github.com/CX0072/molan-desktop/issues/new/choose)

> 后续版本请优先从[最新发行页](https://github.com/CX0072/molan-desktop/releases/latest)下载；本页直链目前对应 0.1.6。

## 适合怎样的作者？

- 想在一个工作台里管理作品、章节和人物等六库设定。
- 想用自己的云模型 Key，或连接本机 Ollama，进行对话、总编任务与分段写作。
- 希望稿件保存在自己授权的电脑目录中，并能导出和备份。

这里的重点是把写作资料与创作流程连在一起；AI 输出仍需要作者审阅，不保证文学质量或事实完全正确。

## 三步开始

1. **下载安装**：下载 Setup.exe 直接安装，或把 ZIP 完整解压后运行其中的 Setup；无需另外安装 Python、Node 或 Electron。
2. **建立自己的工作台**：注册本机账号，保存恢复密钥，选择并授权自己的稿件目录；先测试保存一章、导出一次、关闭再打开。
3. **按需连接 AI**：在设置中配置自己的 OpenAI 兼容接口、Key 与模型名，或者检测本机 Ollama；软件不附赠云模型额度，也不捆绑本地大模型。

按 **F1** 打开分类使用说明；使用中遇到的问题，也可以从软件内反馈入口记录。

## 常见问题

| 问题 | 说明 |
|---|---|
| 支持什么电脑？ | 目标支持 Windows 10/11 x64；本轮实际安装验收为 Windows 11 x64，其他硬件仍需试用反馈。 |
| 桌面的两个图标是两个软件吗？ | 旧安装可能留下英文和中文快捷方式；若指向同一安装目录，就是同一个软件，只保留一个即可。 |
| 移除快捷方式会丢稿件吗？ | 不会，快捷方式只是入口；不要把安装目录、稿件目录或个人数据当成快捷方式清理。 |
| 怎样重新安装或升级？ | 先保存稿件并备份、退出软件，再覆盖安装到原目录；不要为了升级先卸载，也不要手动删除个人数据。 |
| 首次登录用什么账号？ | 注册自己的本机账号；无通用管理员初始密码，管理端由电脑拥有者单独初始化。 |
| 忘记密码怎么办？ | 使用注册时保存的恢复密钥；密钥也丢失时，需要本机管理员协助。 |
| AI 一定能用吗？ | 需要可用的模型服务；Key、模型名、地址、余额、地区权限和额度都可能影响调用。原生 Anthropic/Dify 专有协议需另提供兼容接口。 |
| 模型服务收费吗？ | 取决于所选服务商和套餐，费用及额度由服务商决定。 |
| 自动更新失败怎么办？ | GitHub 不可达或匿名 API 请求受限时，请稍后再试，或从正式发行页手动下载安装。 |
| 安装提示未知发布者？ | 当前安装程序未代码签名；请核对官方来源，并用发行附件中的 SHA256.txt 校验安装程序。 |

## 数据与隐私

稿件默认写入用户授权的本机目录，账号和配置也属于当前电脑；请定期导出独立备份。
**使用云模型时，选中的对话和参考资料会发送给相应服务商**，因此不应把云模型使用过程理解为全程离线。
Windows 云 Key 使用本机账户保护，跨电脑或跨 Windows 账户迁移时需重新配置。

安装包不包含开发者账号、私人稿件或云 Key；本仓库主要分发安装程序与公开说明，当前未在这里发布项目源码。

## 试用与反馈

本轮包含本机覆盖安装、数据保留、账号权限、HTTP 安全、更新传输与真实公网下载等验证；完整范围见[发行说明](https://github.com/CX0072/molan-desktop/releases/latest)。
跨真实物理电脑、不同显卡和长期真人写作仍待反馈，不承诺零漏洞或适配所有模型。

欢迎提交具体的写作困难、步骤或改进建议：[新建反馈](https://github.com/CX0072/molan-desktop/issues/new/choose)。
**公开反馈前，请移除密码、恢复密钥、API Key、私人稿件和个人文件路径；软件内的本机反馈不会自动同步到 GitHub。**

---

Molan Creative Studio is a Windows desktop workspace for Chinese novel writing, chapter and story reference management, with user-configured cloud AI or local Ollama integration. See Releases for downloads; this repository currently distributes binaries and documentation.
