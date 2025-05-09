
# 社媒助手

日常工作中，经常会有从需要各社媒平台采集数据的场景，在使用量不大的情况下，手动处理，太麻烦；用其他产品，可能很贵或需要自己配置非常复杂的开发环境。

所以，本人开发了社媒助手插件，只需在浏览器上安装此插件，即可实现数据采集的自给自足。无需进行任何额外的操作！

## 功能列表

|   平台   | 无水印视频/图片下载 | 采集指定作品的数据 | 采集指定作品的评论 | 采集指定创作者的数据 | 采集指定创作者的作品 |
| :------: | :-----------------: | :----------------: | :----------------: | :------------------: | :------------------: |
|  小红书  |          ✅          |         ✅          |         ✅          |          ✅           |          ✅           |
|   抖音   |          ✅          |         ✅          |         ✅          |          ✅           |          ✅           |

## 使用教程

推荐优先使用商店版，如无法满足要求再使用开源版自行修改！

> 由于种种原因，自0.0.7版本开始，不再开源完整代码，开源版将继续维护数据采集相关功能供大家学习和参考，其余新增功能将主要维护于商店版。

- **Chrome**：<https://chrome.google.com/webstore/detail/dbichmdlbjdeplpkhcejgkakobjbjalc>
- **Edge**：<https://microsoftedge.microsoft.com/addons/detail/gneijakmdhgakglgogbpldbjhbeddibj>
- **其他浏览器**：下载最新版的[社媒助手](https://smc.iszhouhua.com/changelog.html)文件，手动加载到浏览器中

## 二次开发

项目运行需要`NodeJS`，请自行安装运行环境。

> 推荐使用pnpm，也可使用其他依赖管理工具，如：npm、yarn、cnpm等

```bash
# 安装依赖
pnpm install
# 运行项目
pnpm dev
```

项目运行后会自动打开本机的Chrome浏览器，并自动加载插件代码。

项目核心框架为[WXT](https://github.com/wxt-dev/wxt)，具体可见：[WXT文档](https://wxt.dev)

## 打赏

如果觉得项目不错的话可以打赏哦。您的支持就是我最大的动力！

[点击前往打赏](https://alms.iszhouhua.com)

## 联系作者

- Telegram交流群：[点击加入群组](https://t.me/SocialMediaCopilot)

- QQ交流群：[839137339](https://smc.iszhouhua.com/images/qq-group-qr-code.jpg)

- 微信交流群：[点击扫码进群](https://smc.iszhouhua.com/images/wechat-group-qr-code.jpg)

- 作者微信：[iszhouhua](https://smc.iszhouhua.com/images/wechat-qr-code.jpg)

> 添加微信请记得备注来意！

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=iszhouhua/social-media-copilot&type=Date)](https://star-history.com/#iszhouhua/social-media-copilot&Date)

## ⚠️ 免责声明

本项目仅供学习和研究目的，不得用于任何商业活动。用户在使用本项目时应遵守所在地区的法律法规，对于违法使用所导致的后果，本项目及作者不承担任何责任。

本项目可能存在未知的缺陷和风险（包括但不限于设备损坏和账号封禁等），使用者应自行承担使用本项目所产生的所有风险及责任。 作者不保证本项目的准确性、完整性、及时性、可靠性，也不承担任何因使用本项目而产生的任何损失或损害责任。

使用本项目即表示您已阅读并同意本免责声明的全部内容。如果您对上述声明有任何疑问或不同意，请不要使用本项目的代码和功能。如果您使用了本项目的代码和功能，则视为您已完全理解并接受上述免责声明，并自愿承担使用本项目的一切风险和后果。

本项目的知识产权归开发者所有。本项目受到著作权法和国际著作权条约以及其他知识产权法律和条约的保护。用户在遵守本声明及相关法律法规的前提下，可以下载和使用本项目。

关于本项目的最终解释权归开发者所有。开发者保留随时更改或更新本免责声明的权利。
