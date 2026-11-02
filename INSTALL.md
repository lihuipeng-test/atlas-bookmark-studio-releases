# 安装与升级

## 第一次安装

1. 在 [Release 页面](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/releases) 下载名为 `atlas-bookmark-studio-版本号.zip` 的附件，不要下载自动生成的 Source code ZIP。
2. 完整解压到固定文件夹，确认文件夹内直接能看到 `manifest.json`。安装后不要移动或删除这个文件夹。
3. 在 Chrome 地址栏输入 `chrome://extensions`，开启“开发者模式”。
4. 点击“加载已解压的扩展程序”，选择上述文件夹。
5. 打开或刷新国服／国际服的 POE1／POE2 官方市集页面，按左侧的新手引导开始。

ZIP 用于加载已解压扩展，不能直接拖进 Chrome 当成商店扩展安装。当前没有浏览器商店上架版本。

## 从旧版升级

1. 在“设置 → 备份与恢复”确认电脑备份可用，保留最新 JSON。
2. 将新 ZIP 中的文件覆盖到原扩展文件夹，保持原路径。
3. 在 `chrome://extensions` 点击原扩展的“重新加载”，然后刷新市集页面。

不要先移除旧扩展。改用新文件夹可能被浏览器视为独立扩展，无法自动接管原书签、草稿和 AI 连接；正式书签可通过完整 JSON 备份恢复。

## 开启电脑备份

进入“设置 → 备份与恢复”，选择专用文件夹并允许保存。正式修改书签后会自动写入最新 JSON，并保留最近50个历史版本。浏览器重新要求文件权限时，按界面提示恢复授权。

未完成的 AI 清单是当前扩展的本机草稿；保存成书签后才进入书签 JSON 备份。

## 使用 AI

基础条件可以不配置模型直接生成。复杂描述可在“AI → 更多 → AI 设置”填写自己的火山方舟 API Key 和已开通模型的 Model ID，然后保存并测试连接。请先在自己的方舟账户确认模型和费用。

每行描述一件装备，生成后检查条件；必要时预览到官网补全并执行搜索，再采用实际条件。权重只使用你明确提供的数值，不自动计算 PoB 收益。

## 文件校验与反馈

每个 Release 同时提供 `.zip.sha256` 文件。Windows PowerShell 可使用 `Get-FileHash -Algorithm SHA256 -LiteralPath '安装包的完整路径'` 核对 SHA-256。

问题反馈：[GitHub Issues](https://github.com/lihuipeng-test/atlas-bookmark-studio-releases/issues/new/choose)。请不要上传 API Key、密码、Cookie 或私人备份。
