# EdgeEver Notion Minimal

EdgeEver 无代码主题：接近 Notion 的极简观感。纯声明式 JSON，只改 Design Token，不含 CSS / JS。

仅 Web + 桌面端。Android / iOS 原生不跑主题扩展。

## 安装

EdgeEver「插件市场」粘贴仓库地址：

```text
https://github.com/chuyiyue/edgeever-notion-minimal
```

或用 Manifest raw URL：

```text
https://raw.githubusercontent.com/chuyiyue/edgeever-notion-minimal/v1.0.0/manifest.json
```

Release：https://github.com/chuyiyue/edgeever-notion-minimal/releases/tag/v1.0.0

## 设计

- 内容优先，几乎无装饰
- 暖白 / 暖灰背景，近黑文字
- 蓝色是唯一强强调色
- 圆角 4px，密度 `1.05`，编辑区宽 720px
- 浅色 / 深色都覆盖

Token 覆盖三栏、编辑器、图表、表格、海报、AI 侧栏、插件面板、设置、命令面板、通知。布局结构、图标、动画由宿主控制，主题改不了。

## Manifest

- `id`: `me.chuyiyue.edgeever-notion-minimal`
- `themeApiVersion`: `1`
- `version`: `1.0.0`

完整 Token 见根目录 `manifest.json`。
