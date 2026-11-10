# 拾荒拓展 / Scavenging Expansion

**简体中文** | [English](README.en.md)

《深空当铺 / Probably Stolen》的技能树、多功能背包与焚化炉 Mod。

本仓库用于**正式版下载和问题反馈**，不提供源码。

- **[下载最新正式版](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/releases/latest)**：在 Assets 中下载 `ScavengerSkills-版本号.zip`，不要下载 GitHub 自动生成的 Source code 压缩包。
- **[中文问题反馈](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/issues/new?template=bug-report.yml)** / [Report a bug in English](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/issues/new?template=bug-report.en.yml)：请说明实际遇到的问题，并上传复现后的 `Player.log`。
- [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3832768562)
- [搭配使用：改造权](https://github.com/eotn00/ProbablyStolen-RetrofitRights)

## 安装与更新（Windows）

1. 退出游戏，先备份存档。
2. 下载 Releases 中的 Mod ZIP，将其中的 `ScavengerSkills` 文件夹解压到游戏安装目录的 `Mods` 下。
3. 确认结构为 `Mods/ScavengerSkills/manifest.xml` 和 `Mods/ScavengerSkills/ScavengerSkills.dll`，不要额外套一层同名目录。
4. 在游戏模组菜单启用，按游戏提示重启。游戏内按 **F8** 打开菜单；详细玩法见包内 `README.txt`。

Steam 可通过“管理 → 浏览本地文件”找到游戏安装目录。也可直接订阅工坊安装。

**不要同时保留工坊版与同 ID 的本地版或测试版。** 本地副本可能覆盖工坊版本；切换来源前先备份存档，退出游戏后处理重复副本。更新本地版时替换 Mod 文件，不删除个人存档。

## 如何反馈问题

先搜索已有 Issues，再使用问题反馈表单，提供：

- 游戏版本、Mod 版本、安装来源，以及其他已启用的 Mod；
- 实际遇到的问题、预期表现和复现步骤；
- **本次发生问题后的完整 `Player.log` 附件**；截图、录像可辅助说明，但不能代替日志。

### 获取 Player.log（Windows）

1. 运行游戏并复现问题。
2. 按 `Win + R`，输入以下路径并回车：

   ```text
   %USERPROFILE%\AppData\LocalLow\Questing Goose Studio\Probably Stolen
   ```

3. 及时复制备份 `Player.log`，然后把它拖入反馈表单的日志输入框。**不要再次启动游戏后才取日志**，旧日志可能被覆盖；必要时同时提供 `Player-prev.log` 并注明。
4. 若 GitHub 不接受 `.log`，将日志压缩为 ZIP，或复制一份改为 `.txt` 后上传。不要只粘贴几行报错或上传日志截图。

Issues 和附件是公开的。上传前检查是否含用户名、个人路径等隐私；必要时仅遮盖敏感信息，保留相关错误及上下文。不要上传密码、令牌或无关个人文件。找不到日志时，请在日志栏说明已检查的路径和无法提供的原因。

## 使用提醒

重置技能前取出工具侧袋内的物品；核废料默认可能引发致命爆炸。兼容性、配置和玩法细节以正式包内说明为准，第三方 Mod 组合不保证全部兼容。反馈时不必先确定是哪个 Mod 的问题，请如实描述现象和启用列表。
