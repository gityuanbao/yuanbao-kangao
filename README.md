# 源宝看稿

> 锐评一下你的稿件

一个用来判断稿件是否有热门潜力的创作工具。选择投稿分区，放入文案，它会找出最容易让观众离开的地方，并告诉你先改哪一处。

第三方创作工具，非哔哩哔哩官方产品。

## 下载

当前版本：**v0.11.3**

| 系统 | 下载 | 适用范围 |
| --- | --- | --- |
| macOS 11+ | [Universal DMG](https://github.com/gityuanbao/yuanbao-kangao/releases/download/desktop-v0.11.3/YuanbaoKangao_0.11.3_macOS_Universal.dmg) | Apple 芯片与 Intel 芯片 |
| Windows 10 / 11 x64 | [EXE 安装包](https://github.com/gityuanbao/yuanbao-kangao/releases/download/desktop-v0.11.3/YuanbaoKangao_0.11.3_Windows_x64_Setup.exe) | 普通用户推荐 |
| Windows 10 / 11 x64 | [MSI 安装包](https://github.com/gityuanbao/yuanbao-kangao/releases/download/desktop-v0.11.3/YuanbaoKangao_0.11.3_Windows_x64_zh-CN.msi) | 企业部署或管理员安装 |

[查看完整发布页](https://github.com/gityuanbao/yuanbao-kangao/releases/tag/desktop-v0.11.3) · [安装说明](https://github.com/gityuanbao/yuanbao-kangao/releases/download/desktop-v0.11.3/Install-Guide-zh-CN.txt) · [SHA-256](https://github.com/gityuanbao/yuanbao-kangao/releases/download/desktop-v0.11.3/SHA256SUMS.txt)

安装包暂未配置 Apple Developer ID 和 Windows 代码签名，首次打开可能出现系统安全提醒。请从本仓库下载，并按发布页中的安装说明处理。

## 使用

1. 安装并打开“源宝看稿”。
2. 在“设置”中选择 AI 服务商，填写对应开放平台的 API Key。
3. 选择投稿分区，粘贴或上传稿件。
4. 点击“开始锐评”，查看最容易掉人的段落和优先修改动作。

API Key 需要来自对应厂商的开放平台。ChatGPT 会员不等于 OpenAI API 额度，Kimi For Coding 订阅密钥也不等于 Kimi 开放平台 API Key。

## 数据与隐私

- API Key、稿件历史和评分结果保存在当前电脑。
- 锐评时，稿件正文会直接发送给你选择的 AI 服务商。
- 当前桌面版不通过源宝看稿项目服务器转发稿件。
- 不要提交保密、敏感或未获授权的内容。

详见 [隐私说明](PRIVACY.md)。

## 仓库与授权

本仓库只提供官方安装包和使用文档，不包含源码、评分逻辑、提示词、校准样本或内部数据。Release 页面自动生成的 `Source code` ZIP/TAR 只包含本下载仓库的文档，不是软件源码。

软件可免费下载和正常使用，但不是开源软件。不得擅自转载安装包、二次销售、冒充官方版本或反向工程；分享时请直接分享本仓库或官方发布页。完整条款见 [最终用户许可协议](EULA.md)。

软件包含的第三方组件仍分别适用其原有许可证，见 [第三方组件说明](THIRD_PARTY_NOTICES.md)。
