# EvoWorld Marketing Design System

## Creative direction

EvoWorld 的营销视觉采用“暗色幻想游戏界面 + 生物进化科技感”的组合：深蓝黑底代表混沌世界，青绿色代表生命能量，金色代表稀有基因与资产价值。页面可直接用于融资路演、众筹预热、合伙人招募与社区冷启动。

## Visual tokens

| Token | Value | Usage |
| --- | --- | --- |
| Background | `#06101c` | 主背景、深色叙事空间 |
| Panel | `rgba(13, 30, 49, 0.76)` | 卡片、机制模块、资产表格 |
| Aqua | `#70ffe2` | 生命能量、主视觉高光、eyebrow |
| Blue | `#3a9dff` | 科技感、按钮渐变、能量 UI |
| Gold | `#f9c74f` | 稀有基因、CTA、经济价值 |
| Text | `#effbff` | 主要标题 |
| Muted | `#9ab9c9` | 长段解释文本 |

## Page structure

1. **Hero**：一句话定位、融资版摘要入口、产品仪表盘概念图。
2. **Problem grid**：解释 Web2、NFT、GameFi 的核心痛点。
3. **Core loop**：用代谢、进化、遗产三张卡建立反熵经济认知。
4. **Asset system**：明确 $DARWIN、EvoSpecies、基因碎片、标本 / 化石的角色。
5. **MVP proof**：把路线压缩为四个可验证事实。
6. **CTA**：引导读者进入冷启动策略与白皮书资料。

## Standalone asset usage

- `assets/logo-mark.svg`：可用作头像、favicon、社区图标、融资 deck 封面角标。
- `assets/hero-dashboard.svg`：可单独用于官网 hero、路演 PPT、社群长图头图。
- `assets/social-share-card.svg`：可用于 Twitter/X、微信、飞书、Notion 分享预览。
- `assets/icon-*.svg`：可拆分用于机制卡片、白皮书插图与信息流海报。

## Production notes

- 当前素材为可编辑 SVG，适合在早期阶段快速迭代与保持清晰度。
- 若后续需要更强视觉冲击，可使用 `README.md` 中的 Imagen prompt pack 生成 PNG/JPG 版本，再替换同名资源或新增 `*-raster.png`。
- 页面未依赖外部字体、CDN 或构建工具，可直接通过静态服务器打开。
