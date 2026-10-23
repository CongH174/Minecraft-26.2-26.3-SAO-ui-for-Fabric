# SAO UI for Fabric

SAO 风格的 Minecraft 界面模组。同一个 JAR 同时支持 **Minecraft 26.2 / 26.3**，无需选择不同构建。

## 下载最新版 · 0.22.0

**[下载统一 JAR](https://github.com/CongH174/Minecraft-26.2-26.3-SAO-ui-for-Fabric/releases/download/v0.22.0/sao-ui-0.22.0%2Bmc26.2-26.3.jar)** · [完整 Release](https://github.com/CongH174/Minecraft-26.2-26.3-SAO-ui-for-Fabric/releases/tag/v0.22.0) · [使用说明](releases/0.22.0/SAO-UI-0.22.0-使用说明.md)

[完整源码 ZIP](releases/0.22.0/sao-ui-0.22.0%2Bmc26.2-26.3-source.zip) · [验证报告](releases/0.22.0/sao-ui-0.22.0%2Bmc26.2-26.3-validation.txt) · [SHA256](releases/0.22.0/SHA256SUMS.txt)

0.22.0 新增右侧 HUD、SAO 切角／纯矩形样式菜单，以及实时角色状态总览；修复附魔原文说明开关反馈，并在界面设置顶部加入可视化布局入口。新选项支持中英文悬停解释与草稿保存／取消。

## 安装

需要 Java 25、Fabric Loader 0.19.3+ 和匹配游戏版本的 Fabric API：26.2 至少 0.152.1+26.2，26.3 至少 0.164.0+26.3。

移除旧版 SAO UI JAR，将新版放入 mods；保留 config/saoui.json。基础 HUD 与菜单只需客户端安装，容器内额外 2×2 合成需要双方安装并协商支持。AppleSkin / IPN 为可选依赖，不包含在成品中。

## 历史版本与仓库目录

**[查看全部版本](releases/README.md)**：每个版本的安装包、源码、说明和校验文件放在同一目录。

```text
releases/
├── README.md        版本索引
├── SHA256SUMS.txt   全部归档文件校验
├── 0.22.0/          最新版、说明与预览图
├── 0.21.0/          历史归档
└── 0.20.0/          历史归档
```

源代码以每版的 `*-source.zip` 保存。现有 Release 下载地址保持可用，整理目录不会修改 JAR 或源码内容。

## 预览

右侧纯矩形 HUD：

![右侧纯矩形 HUD](releases/0.22.0/screenshots/0.22.0-mc26.3-sao-style-rectangle-right.png)

实时角色状态页：

![角色状态页](releases/0.22.0/screenshots/0.22.0-mc26.3-sao-player-status.png)

## 验证与许可

0.22.0 的同一 SHA256 成品已在 26.2 / 26.3 实际加载，每版通过 63 项单元测试、15 组功能测试及统一包身份检查。详见对应版本的验证报告。

GPL-3.0-only，见 [LICENSE](LICENSE)。非官方 SAO 产品。
