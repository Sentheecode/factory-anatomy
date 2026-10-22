# Factory Anatomy

整车厂冲焊涂总等车间的 **等轴测交互 SVG / HTML** 作品集（Factory Anatomy），用于演示、短视频与方案讲解。

Built with the [Anatomy](https://github.com/wheresryan22/anatomy) isometric SVG skill (MIT). This repository is our independent showcase — not a fork of the upstream skill.

## Gallery

### 冲压 Stamping
![冲压线](docs/gallery/01-stamping.png)

### 焊装 Body Shop (BIW)
![焊装车间](docs/gallery/02-bodyshop.png)

### 涂装 Paint Shop（三层）
![涂装车间](docs/gallery/03-paintshop.png)

### 新能源总装 NEV Final Assembly
![总装总览](docs/gallery/04-assembly-nev.png)

双主线（内饰一二等）与板链密接细节：

| 双线 | 板链 | 线上作业 |
|:---:|:---:|:---:|
| ![dual](docs/gallery/04c-assembly-dual.png) | ![plate](docs/gallery/04b-assembly-plate.png) | ![workers](docs/gallery/04d-assembly-workers.png) |

### 电池包线 Battery Pack
![电池包](docs/gallery/05-battery-pack.png)

## What’s inside

| Scene | Interactive HTML (open locally) | Notes |
| --- | --- | --- |
| 冲压 | `figures/stamping-jier-line-light.html` | 济南二机床风格线体 |
| 焊装 | `figures/bodyshop-biw-desktop-light.html` | BIW 总览 |
| 涂装 | `figures/paintshop-3f-desktop-light.html` | 三层：电泳 / 面漆 / 精修 |
| 新能源总装 | `figures/assembly-nev-desktop-light.html` | 整体合装 + 双主线 + 板链 |
| 电池包 | `figures/battery-pack-line-light.html` | Pack 线 |

> Large HTML demos are kept under `figures/` (git-lfs friendly). Prefer browsing screenshots above for a quick look; open HTML in a desktop browser for live animation.

## Credits

- Visual language & kit: [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) (MIT)
- Factory process scenes: Senthee / 吴斌 & assistants (2026)

## License

- Upstream Anatomy kit: MIT (see `LICENSE-anatomy.txt`)
- Our scene content & docs in this repo: MIT (see `LICENSE`)
