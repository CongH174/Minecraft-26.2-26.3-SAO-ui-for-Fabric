# SAO UI for Fabric

SAO 风格的 Minecraft 界面模组。同一个 JAR 同时支持 **Minecraft 26.2 / 26.3**，无需选择不同构建。

## 下载最新版 · 0.23.1

**[下载统一 JAR](https://github.com/CongH174/Minecraft-26.2-26.3-SAO-ui-for-Fabric/releases/download/v0.23.1/sao-ui-0.23.1%2Bmc26.2-26.3.jar)** · [完整 Release](https://github.com/CongH174/Minecraft-26.2-26.3-SAO-ui-for-Fabric/releases/tag/v0.23.1) · [使用说明](releases/0.23.1/SAO-UI-0.23.1-使用说明.md)

[完整源码 ZIP](releases/0.23.1/sao-ui-0.23.1%2Bmc26.2-26.3-source.zip) · [验证报告](releases/0.23.1/sao-ui-0.23.1%2Bmc26.2-26.3-validation.txt) · [SHA256](releases/0.23.1/SHA256SUMS.txt)

- **附魔模式勾选框**：默认显示实际附魔，勾选后预览此物品适用的每条魔咒及最高等级；标注未生效，不修改物品。保留物品原文和放大阅读，移除重复的原版参考区块。
- **AppleSkin 手持食物预览**：预计恢复的饥饿区间呼吸显示，遵循 AppleSkin 的预览、副手和透明度设置。支持左右布局和 SAO／纯矩形血条。
- 保留角色状态总览、独立 HUD 控制、可视化布局、中英文悬停说明及设置草稿保存／取消。

## 安装

需要 Java 25、Fabric Loader 0.19.3+ 和匹配游戏版本的 Fabric API：26.2 至少 0.152.1+26.2，26.3 至少 0.164.0+26.3。

移除旧版 SAO UI JAR，将新版放入 mods；保留 config/saoui.json。基础 HUD 与菜单只需客户端安装，容器内额外 2×2 合成需要双方安装并协商支持。AppleSkin / IPN 为可选依赖，不包含在成品中；食物预览已验证对应版本的 AppleSkin 3.0.10。

## 历史版本与仓库目录

**[查看全部版本](releases/README.md)**：每个版本的安装包、源码、说明、截图和校验文件放在同一目录。

```text
releases/
├── README.md        版本索引
├── SHA256SUMS.txt   全部归档文件校验
├── 0.23.1/          最新版、说明与预览图
├── 0.22.0/          历史归档
├── 0.21.0/          历史归档
└── 0.20.0/          历史归档
```

源代码以每版的 `*-source.zip` 保存。历史文件与 Release 下载地址继续保留。

## 预览

附魔最高等级预览：

![附魔模式勾选框](releases/0.23.1/screenshots/0.23.1-mc26.3-sao-enchantment-max-checked.png)

手持食物呼吸预览：

![食物恢复预览](releases/0.23.1/screenshots/0.23.1-mc26.3-sao-food-preview-rectangle-right.png)

## 验证与许可

0.23.1 的同一 SHA256 成品已在 26.2 / 26.3 实际加载，每版通过 69 项单元测试、17 组完整功能测试及统一包身份检查，并补充未安装 AppleSkin 的检查。详见版本验证报告。

GPL-3.0-only，见 [LICENSE](LICENSE)。非官方 SAO 产品。
