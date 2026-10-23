# Factory Anatomy

整车厂冲焊涂总等车间的 **等轴测交互 SVG / HTML** 作品集，用于演示与方案讲解。

基于 [Anatomy](https://github.com/wheresryan22/anatomy) isometric SVG skill（MIT）的独立展示仓，非上游 fork。

**Live site:** [https://sentheecode.github.io/factory-anatomy/](https://sentheecode.github.io/factory-anatomy/) — 浏览画廊并打开各场景交互 HTML。

## Gallery

| 场景 | 预览 | 说明 |
| :--- | :---: | :--- |
| **冲压** Press Shop | <img src="docs/gallery/01-stamping.png" width="320" alt="冲压线"> | 五连冲压线 · AGV 下料 |
| **焊装** Body Shop | <img src="docs/gallery/02-bodyshop.png" width="320" alt="焊装车间"> | BIW 总览 |
| **涂装** Paint Shop | <img src="docs/gallery/03-paintshop.png" width="320" alt="涂装车间"> | 三层：电泳 / 面漆 / 精修 |
| **总装** Assembly Shop | <img src="docs/gallery/04-assembly-nev.png" width="320" alt="总装总览"> | 整体合装 · 双主线 · 板链 |
| **电池包** Battery Pack | <img src="docs/gallery/05-battery-pack.png" width="320" alt="电池包"> | Pack 线 |
| **电驱** Electric Drive Shop (EDS) | <img src="docs/gallery/06-eds.png" width="320" alt="电驱车间"> | 电驱车间总览 · 三合一总成爆炸图 |

## What’s inside

| Scene | Interactive HTML | Notes |
| --- | --- | --- |
| 冲压 Press Shop | `figures/stamping-jier-line-light.html` | 五连冲压线 |
| 焊装 Body Shop | `figures/bodyshop-biw-desktop-light.html` | BIW 总览 |
| 涂装 Paint Shop | `figures/paintshop-3f-desktop-light.html` | 三层：电泳 / 面漆 / 精修 |
| 总装 Assembly Shop | `figures/assembly-nev-desktop-light.html` | 整体合装 + 双主线 + 板链 |
| 电池包 Battery Pack | `figures/battery-pack-line-light.html` | Pack 线 |
| 电驱 Electric Drive Shop (EDS) | `figures/edu-drive-desktop-light.html` | 电驱车间总览 |
| 电驱 Electric Drive Shop (EDS) — product unit | `figures/edu-drive-unit-light.html` | 三合一总成爆炸图 |

> 大体积 HTML 在 `figures/`。快速浏览用上表截图；要看动画请在桌面浏览器打开 HTML。

## Credits

- Visual language & kit: [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) (MIT)
- Factory process scenes: Senthee / 吴斌 & assistants (2026)

## License

- Upstream Anatomy kit: MIT（见 `LICENSE-anatomy.txt`）
- 本仓场景与文档：MIT（见 `LICENSE`）
