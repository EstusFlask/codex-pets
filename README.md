# Codex Pets

Custom animated pet assets for Codex, featuring **Taiga Aisaka / 逢坂大河** and **Koromo Amae / 天江衣**.

Codex 自定义动画桌宠素材，包含逢坂大河与天江衣。

## Pet folders / 桌宠目录

| Character / 角色 | Folder / 目录 |
| --- | --- |
| Taiga Aisaka / 逢坂大河 | [`aisaka-taiga/`](aisaka-taiga/) |
| Koromo Amae / 天江衣 | [`amae-koromo/`](amae-koromo/) |

Each folder contains a `pet.json` manifest and a `spritesheet.webp` animation sheet. Keep these files together: the manifest uses a relative `spritesheetPath`. Both manifests declare `spriteVersionNumber: 2`.

每个目录都包含 `pet.json` 清单与 `spritesheet.webp` 动画精灵图。使用时保留目录结构和两个文件的相对位置；清单中的精灵图路径为相对路径。

The `aisaka-taiga-output/` and `amae-koromo-output/` directories contain generation and validation artifacts. The two pet folders above contain the ready-to-use manifest/spritesheet pairs; this repository is an asset collection rather than a standalone application.

带 `-output` 后缀的目录保存生成和校验记录；实际桌宠素材使用上表中的两个目录。本仓库提供素材，不包含独立运行程序。
