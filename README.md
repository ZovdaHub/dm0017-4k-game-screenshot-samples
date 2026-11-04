# DM0017 · 4K Game Screenshot Samples / 4K 游戏截图样例

**Dataset card / 数据集卡片** · Zovda sample dataset. This repository is the GitHub mirror of the card; the data files are hosted on Hugging Face — **[download the dataset / 下载数据集](https://huggingface.co/datasets/Zovda/dm0017-4k-game-screenshot-samples)**.

本仓库是数据集卡片的 GitHub 镜像，数据文件托管在 Hugging Face，**[点击下载 / download](https://huggingface.co/datasets/Zovda/dm0017-4k-game-screenshot-samples)**。

| Item / 项目 | Value / 值 |
|---|---|
| Dataset ID / 数据集编号 | DM0017 |
| Files / 数据文件 | 20 |
| Size / 数据体积 | 196.98 MB |
| Language / 语言 | en |
| Tasks / 任务类别 | image-classification, text-to-image |
| Hugging Face / 数据地址 | [dm0017-4k-game-screenshot-samples](https://huggingface.co/datasets/Zovda/dm0017-4k-game-screenshot-samples) |
| Provided by / 提供方 | Zovda |
| Contact / 联系邮箱 | lucas@zovda.com |

## Overview / 简介

20 native 3840×2160 game screenshots from Cyberpunk 2077 and The Witcher 3: Songs of the Past, for image understanding, art-style evaluation and text-to-image benchmarking.

20 张原生 3840×2160 游戏画面截图，覆盖《赛博朋克 2077》与《巫师 3：往日之歌》，用于图像理解、画风评估与文生图评测。

## What's inside / 数据内容

- 20 screenshots under `4k/` (18 PNG + 2 JPEG), grouped by title and asset type.
- `4k/` 目录下 20 张截图（18 PNG + 2 JPEG），按作品与素材类型分组。
- 17 are official press assets without HUD; 3 are Photo Mode update assets carrying full English UI, with frame 20 in Simplified Chinese branding.
- 其中 17 张为无 HUD 的官方媒体素材，3 张为 Photo Mode 更新素材（含完整英文 UI，第 20 张为简体中文版本）。

## Specifications / 规格

- Resolution: native 3840×2160 (16:9), no upscaling, cropping, letterboxing or watermarks
- 分辨率：原生 3840×2160（16:9），无放大、无裁切、无黑边与水印
- 5.01–29.40 MB per frame, 196.98 MB total
- 单张 5.01–29.40 MB，合计 196.98 MB

## Suitable tasks / 适用任务

- 4K image understanding and scene classification
- 4K 图像理解与场景分类
- Art-style and aesthetic evaluation
- 画风与画面美学评估
- High-resolution reference and evaluation for text-to-image / image-to-image
- 文生图/图生图高分辨率参考与评测
- Game-UI element detection and OCR validation
- 游戏 UI 元素识别与 OCR 验证

## Files / 文件清单

Paths below are relative to the Hugging Face repository root. 下表路径相对于 Hugging Face 仓库根目录。

| # | File | Size |
|---|---|---|
| 1 | `game-screenshots/4k/01_Cyberpunk2077_PS5_Pro_CLEAN.png` | 29.40 MB |
| 2 | `game-screenshots/4k/02_Cyberpunk2077_PS5_Pro_Turn_Back_CLEAN.png` | 8.40 MB |
| 3 | `game-screenshots/4k/03_Cyberpunk2077_PS5_Pro_Columns_CLEAN.png` | 9.85 MB |
| 4 | `game-screenshots/4k/04_Cyberpunk2077_PS5_Pro_Cynosure_CLEAN.png` | 7.83 MB |
| 5 | `game-screenshots/4k/05_Cyberpunk2077_PS5_Pro_Jackie_CLEAN.png` | 10.71 MB |
| 6 | `game-screenshots/4k/06_Cyberpunk2077_PS5_Pro_Misty_CLEAN.png` | 9.50 MB |
| 7 | `game-screenshots/4k/07_Cyberpunk2077_PS5_Pro_Reed_CLEAN.png` | 6.83 MB |
| 8 | `game-screenshots/4k/08_Cyberpunk2077_PS5_Pro_Smasher_CLEAN.png` | 8.65 MB |
| 9 | `game-screenshots/4k/09_W3SoP_Gamescom_Garden_of_Thorns_1_PC_16x9_CLEAN.png` | 12.01 MB |
| 10 | `game-screenshots/4k/10_W3SoP_Gamescom_Garden_of_Thorns_2_PC_16x9_CLEAN.png` | 9.88 MB |
| 11 | `game-screenshots/4k/11_W3SoP_Gamescom_Geralt_fighting_PC_16x9_CLEAN.png` | 9.26 MB |
| 12 | `game-screenshots/4k/12_W3SoP_Gamescom_Geralt_fighting_Swarmion_PC_16x9_CLEAN.jpeg` | 6.82 MB |
| 13 | `game-screenshots/4k/13_W3SoP_Gamescom_Geralt_using_Chain_PC_16x9_CLEAN.jpeg` | 7.31 MB |
| 14 | `game-screenshots/4k/14_W3SoP_Gamescom_Letten_Vista_1_PC_16x9_CLEAN.png` | 10.99 MB |
| 15 | `game-screenshots/4k/15_W3SoP_Gamescom_Letten_Vista_2_PC_16x9_CLEAN.png` | 14.16 MB |
| 16 | `game-screenshots/4k/16_W3SoP_Gamescom_Lettenhove_PC_16x9_CLEAN.png` | 12.96 MB |
| 17 | `game-screenshots/4k/17_W3SoP_Wood_Witch_PC_16x9_CLEAN.png` | 6.92 MB |
| 18 | `game-screenshots/4k/18_CP2077_UPDATE_2.2_Photomode_PS5_EN_v1.png` | 5.25 MB |
| 19 | `game-screenshots/4k/19_CP2077_UPDATE_2.2_XSX_S_Photomode_EN_v1.png` | 5.01 MB |
| 20 | `game-screenshots/4k/20_CP2077_UPDATE_2.2_Photomode_PS5_ZHS_v1.png` | 5.26 MB |

## Download / 下载

The files are not stored in this repository. 数据文件不在本仓库内，请从 Hugging Face 获取。

- Dataset page / 数据集页面: https://huggingface.co/datasets/Zovda/dm0017-4k-game-screenshot-samples
- Direct file URL / 单文件直链: `https://huggingface.co/datasets/Zovda/dm0017-4k-game-screenshot-samples/resolve/main/<path from MANIFEST.csv>`

```python
from huggingface_hub import snapshot_download

snapshot_download(
    repo_id="Zovda/dm0017-4k-game-screenshot-samples",
    repo_type="dataset",
    local_dir="./dm0017-4k-game-screenshot-samples",
)
```

```python
from huggingface_hub import hf_hub_download

hf_hub_download(
    repo_id="Zovda/dm0017-4k-game-screenshot-samples",
    repo_type="dataset",
    filename="<path from MANIFEST.csv>",
    local_dir="./dm0017-4k-game-screenshot-samples",
)
```

## Rights and disclaimer / 授权与声明

All files originate from the CD PROJEKT RED public Press Center and remain the property of the rightsholder. This dataset only demonstrates collection quality, image types and delivery records; **it grants no licence for model training or redistribution**.

全部文件来自 CD PROJEKT RED 公开 Press Center，著作权归原权利人所有。本数据集仅用于展示采集质量、画面类型与交付记录格式，**不构成可用于模型训练或再分发的版权授权**。

This dataset is shared to demonstrate data organisation, technical specifications and delivery structure. For formal licensing, large-scale access or custom production, contact lucas@zovda.com.

本数据集仅用于展示数据组织方式、技术规格与交付结构。正式授权、规模化取数与定制生产请联系 lucas@zovda.com。

## About Zovda / 关于 Zovda

Zovda builds, cleans, annotates and packages training data across video, audio, images, e-commerce image-text pairs, exam question banks, embodied AI and coding-agent corpora.

Zovda 提供多模态与文本训练语料的数据采集、清洗、标注与结构化交付服务，覆盖视频、音频、图像、电商图文、K12 与职业题库、具身智能、代码智能体等方向。

**Contact / 联系方式:** lucas@zovda.com
