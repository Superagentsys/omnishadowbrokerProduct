# OmniShadow Broker

公开下载仓。这里只放**编译好的桌面安装包**和产品说明，不放源码。

源码仓库（私有）：[Superagentsys/omnishadowbroker](https://github.com/Superagentsys/omnishadowbroker)

当前版本：**v0.1.6**

## 下载

安装包挂在 [Releases](https://github.com/Superagentsys/omnishadowbrokerProduct/releases)（也同步到本仓 `releases/v0.1.6/`，若体积允许）。

| 平台 | 文件 |
|---|---|
| macOS Apple Silicon | `omnishadow-broker_0.1.6_macos-apple_*.dmg` |
| macOS Intel | `omnishadow-broker_0.1.6_macos-intel_*.dmg` |
| Windows x64 | `omnishadow-broker_0.1.6_windows-x64_*.exe` / `*.msi` |

macOS 若提示未验证开发者：系统设置 → 隐私与安全性 → 仍要打开。

## 这是什么

本机部署的多源地理情报工作台。浏览器或桌面窗口只连本机网关，公开 OSINT 由本机聚合。密钥写在本机 `~/.omninova/`，不要提交到任何仓库。

- 态势图：航空、地震、台风、预警、轨道、人道与地缘等公开图层
- 舆情监测：热榜 / RSS，失败时保留上次结果
- AI 搜索、智能体只读接入、简报拟稿

工作底稿来自公开源，非正式公文、非正式密件。

## 本机端口

默认网关 **10829**。不要占用其他 Omni 产品已经在用的 `10809` / `5173`。

## 许可

MIT。见 [LICENSE](LICENSE)。
