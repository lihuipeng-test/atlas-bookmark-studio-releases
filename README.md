# Atlas Bookmark Studio

**给 POE 玩家和 BD 作者使用的装备购买书签工具。**

在官方交易页管理购买路线，把多件装备需求生成搜索条件，核对后一次保存。

## 下载

### [下载 0.20.14 公开试用版](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/releases/download/v0.20.14/atlas-bookmark-studio-0.20.14.zip)

[版本说明与附件](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/releases/tag/v0.20.14) · [历史版本](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/releases) · [安装与升级](INSTALL.md) · [反馈问题](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/issues/new/choose)

**请下载 `atlas-bookmark-studio-0.20.14.zip`。GitHub 自动附带的 `Source code` ZIP 不是可安装的扩展包。**

## 能做什么

- 在 POE1／POE2 的国服、国际服官方市集页面，用目录管理搜索书签。
- 每行描述一件装备，一次最多12件；核对、预览并批量保存。
- 支持属性最低值、抗性任选、预算、排序，以及作者明确填写的权重。
- 在官网继续调整并执行搜索后，将实际条件保存回书签。
- 以已有书签为基础，只修改明确的数值、预算或排序，保留其他搜索条件；这类修改无需 AI。
- 勾选装备后复制、移动、删除，或另建下一阶段，支持操作后的撤销。
- 展开目录就地阅读阶段说明，查看作者填写的沿用、替换和购买数量安排。
- 复制目录、跨服另存和分享购买方案，常用工具可自定义。
- 同时关注最多 8 个搜索，按书签查看实时商品和标价。
- 开启电脑文件夹自动备份，正式修改后更新并校验一份最新 JSON。

基础条件无需 AI Key。复杂描述可以接入你自己的火山方舟 API Key 和已开通模型，调用费用由你的方舟账户承担。工具不计算 PoB 收益权重；购买前仍需核对条件、词缀、价格和库存。

## 三步安装

1. 下载上面的扩展 ZIP，完整解压到一个固定文件夹。
2. 打开 Chrome 的 `chrome://extensions`，开启“开发者模式”，点击“加载已解压的扩展程序”。
3. 选择直接包含 `manifest.json` 的文件夹，打开或刷新官方市集页面。

已有用户请按 [升级说明](INSTALL.md#从旧版升级) 覆盖原文件夹并重新加载，**不要先移除旧扩展**。

## 0.20.14 更新 · 2026-11-19

- 实时关注支持分组报价，点击商品「详情」打开对应的已有官网实时页，关闭后清空本次关注。
- 恢复经典羊皮纸，标准行距默认开启。目录与赛季同行，说明按需展开。
- 在同一阶段混排购买书签、说明、正则和子目录。正则支持点击复制。
- 快捷工具支持自定义，跨服复制可从列表选择赛季。

新版可以读取旧版分享及备份。共享新版目录或在另一台电脑恢复全量备份前，请先将接收方扩展升级到本版。

## 数据和反馈

书签主要保存在本机，建议完成侧栏的电脑备份引导。未完成的 AI 清单和目录说明是本机草稿，保存成正式内容后才进入书签 JSON 备份。当前没有开发者运营的云同步或账号服务。复杂 AI 请求会直接发送到你配置的火山方舟服务，详情见下载包中的 `PRIVACY.html`。

遇到问题请 [提交反馈](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/issues/new/choose)，附上浏览器和扩展版本、游戏与区服、原始购买描述及错误提示。**不要提供 API Key、密码、Cookie 或整份私人书签备份。**

本仓库只用于公开下载、使用说明和问题反馈，不存放项目开发历史。本工具独立开发，不代表游戏或交易网站官方。
