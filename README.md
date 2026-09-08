# 视频号视频一键下载

[![version](https://img.shields.io/badge/version-1.1.5-2563eb)](https://skillhub.cn/skills/wechat-channels-downloader)
[![downloads](https://img.shields.io/badge/downloads-1k%2B-2fbf8f)](https://skillhub.cn/skills/wechat-channels-downloader)
[![platform](https://img.shields.io/badge/platform-SkillHub-5b8ff9)](https://skillhub.cn/skills/wechat-channels-downloader)
[![license](https://img.shields.io/badge/license-MIT-22c55e)](./LICENSE)

> 一键把你有权处理的微信视频号视频，原画质下载到本地。支持批量、自动去重。

> [!IMPORTANT]
> **本仓库是技能索引与说明页，代码与安装包不在 GitHub。**
> 完整可用的技能包请在 SkillHub 获取（一键安装，自动跟随版本更新）：
>
> 👉 **https://skillhub.cn/skills/wechat-channels-downloader**

---

## 3 秒判断：这是不是你要的

| 如果你正遇到 | 这个技能替你做的事 |
|---|---|
| 收藏的好视频怕作者删了 | 下载原始 mp4 到本地永久保存 |
| 一次要存十几条 | 批量粘贴多个链接，自动挨个跑 |
| 重复下载浪费时间 | 自动跳过已下载链接（断点续传） |
| 下载完文件名一团乱 | 统一命名：`{平台}_{作者}_{短标题}_{日期}.mp4` |

**一句话定位**：给「收藏了好视频怕被删」的人用的本地归档工具。

---

## 核心能力

- **原画质下载** —— 拿到的是原始 mp4，不是二次压缩版
- **批量处理** —— 一次粘贴多个链接，自动排队
- **断点续传** —— 自动跳过已下载的链接，不重复跑
- **规范命名** —— 文件名自带平台 / 作者 / 标题 / 日期，便于检索
- **默认输出目录** —— Windows 落在 `K:\视频号下载`，其他系统落到 `./output`

---

## 三步上手

1. 在微信里打开视频，点「复制链接」
2. 把链接粘贴进去（多条可一次粘完）
3. 等待下载完成，文件就在输出目录里了

---

## 合规与边界

**只支持**：

- 你自己发布过的视频号视频
- 已获原作者授权下载的内容
- 你已经收藏到本地的视频

**不支持**：

- 付费内容、会员专享、私密账号
- 任何你拿不到授权的他人作品

下载他人作品须先取得版权方许可，否则构成侵权，责任由使用者承担。

---

## 安装（唯一入口）

技能的运行脚本、依赖与后续更新都托管在 SkillHub，那里是唯一的安装来源。

### 👉 [在 SkillHub 安装「视频号视频一键下载」](https://skillhub.cn/skills/wechat-channels-downloader)

安装后在工作台搜索 `wechat-channels-downloader` 即可调用。

---

## 常见问题

**Q：为什么 GitHub 上找不到源码？**
A：本仓库只做索引与说明（见下方「关于这个仓库」）。可运行的技能包统一在 SkillHub 分发，避免你 clone 到一个跑不起来的旧快照。

**Q：能下载别人的视频吗？**
A：只能下你有权处理的内容（自己发布的 / 已授权的 / 本地收藏的）。付费与私密内容不支持。

**Q：下载到哪个目录？**
A：Windows 默认 `K:\视频号下载`，其他系统 `./output`。

---

## 关于这个仓库

这个仓库只做两件事：

1. **门牌** —— 让你在 GitHub 或搜索引擎里能找到这个技能
2. **展示窗** —— 让你在看代码之前，就能判断它值不值得装

技能本体（脚本、依赖、更新）全部在 SkillHub，保证你装到的永远是最新版。

- SkillHub 主页：https://skillhub.cn/skills/wechat-channels-downloader
- 问题反馈：请在 SkillHub 技能页留言

## License

[MIT](./LICENSE)
