# SAO UI for Fabric

SAO 风格的 Minecraft 界面模组。同一个 JAR 同时支持 **Minecraft 26.2 / 26.3**。

## 下载最新版 · 0.26.0

**[下载统一 JAR](https://github.com/CongH174/Minecraft-26.2-26.3-SAO-ui-for-Fabric/releases/download/v0.26.0/sao-ui-0.26.0%2Bmc26.2-26.3.jar)** · [完整 Release](https://github.com/CongH174/Minecraft-26.2-26.3-SAO-ui-for-Fabric/releases/tag/v0.26.0) · [使用说明](releases/0.26.0/SAO-UI-0.26.0-使用说明.md)

[完整源码 ZIP](releases/0.26.0/sao-ui-0.26.0%2Bmc26.2-26.3-source.zip) · [验证报告](releases/0.26.0/sao-ui-0.26.0%2Bmc26.2-26.3-validation.txt) · [SHA256](releases/0.26.0/SHA256SUMS.txt)

- **伽马复写**：默认按 **G** 切换，提供类似夜视的暗处高亮，可在原版按键绑定中改键。与 K 菜单独立，默认关闭、退出世界自动关闭；关闭后恢复当前原版亮度。
- **附魔说明**：重写全部 43 种原版魔咒的中英文效果说明，明确适用目标、条件和当前等级数值；服务器修改的效果继续按实际同步数据解释。保留实际附魔／最高等级预览勾选框。
- **装备与角色页面**：扩大说明区域，调整装备目录，保留选择与阅读位置，增加明确的放大阅读按钮；角色页面支持定位低耐久装备与查看完整状态效果。
- **设置与布局**：增加分类内搜索、修改提示和明确的保存／放弃文字，布局入口共享设置草稿；HUD 编辑器可显示辅助参考。
- **菜单动画**：保持原有动画逻辑，继续由现有动画开关和速度滑块控制。

保留 AppleSkin 手持食物呼吸预览、左右 HUD、SAO／纯矩形血条、可视化布局及中英文设置悬停说明。

## 安装

需要 Java 25、Fabric Loader 0.19.3+，以及匹配游戏版本的 Fabric API：26.2 至少 0.152.1+26.2，26.3 至少 0.164.0+26.3。

移除旧版 SAO UI JAR，将新版放入 mods；保留 config/saoui.json。基础 HUD 与菜单只需客户端安装，容器内额外 2×2 合成需要双方安装并协商支持。AppleSkin / IPN 为可选依赖。

## 历史版本与仓库目录

**[查看全部版本](releases/README.md)**：每个版本的安装包、源码、说明、截图和校验文件放在同一目录。

```text
releases/
├── README.md        版本索引
├── SHA256SUMS.txt   全部归档文件校验
├── 0.26.0/          最新版、说明与预览图
├── 0.23.1/          历史归档
├── 0.22.0/          历史归档
├── 0.21.0/          历史归档
└── 0.20.0/          历史归档
```

源代码以每版的 `*-source.zip` 保存。历史文件与 Release 下载地址继续保留。

## 伽马复写预览

同一暗室，关闭时：

![伽马关闭](releases/0.26.0/screenshots/0.26.0-mc26.3-sao-gamma-off.png)

按 G 开启后：

![伽马开启](releases/0.26.0/screenshots/0.26.0-mc26.3-sao-gamma-on.png)

## 验证与许可

同一个 SHA256 的统一 JAR 已在 Minecraft 26.2 和 26.3 实际加载，选中的运行时来源均为 NESTED/saoui。每版通过 77 项单元测试，本次功能测试覆盖伽马开关、改键、真实暗室亮度、关闭恢复、菜单输入隔离、退出世界关闭及统一包身份。验证沿用已完成记录，没有重复运行无关模组兼容测试；自定义光影管线尚未验证。

GPL-3.0-only，见 [LICENSE](LICENSE)。非官方 SAO 产品。
