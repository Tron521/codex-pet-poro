# Codex Pet: Poro

一个为 Codex Desktop 制作的自定义魄罗桌宠。它参考了《英雄联盟》中魄罗的经典形象，并重新绘制成适合 Codex 桌宠系统的小尺寸像素风动画：圆滚滚的白色毛球身体、浅棕色小角、黑色豆豆眼、粉色小舌头和短短的小蹄子。

This is a custom Codex Desktop pet inspired by the League of Legends Poro, redrawn as a compact pixel-art-style animated companion for the Codex pet system.

## 中文说明

### 简介

`Poro` 是一个 Codex Desktop 自定义桌宠包，适合想在 Codex 里放一个轻量、可爱、低干扰工作伙伴的场景。它包含完整的 `9` 行动画状态，覆盖待机、左右移动、挥手、跳跃、失败/难过、等待、执行任务和 review 状态。

这个桌宠不是简单截图或静态图片，而是按 Codex 桌宠规格整理好的透明 spritesheet。每一帧都被放进固定的 `192 x 208` 单元格，最终 atlas 尺寸为 `1536 x 1872`，可以直接被 Codex Desktop 读取。

### 安装方式

把仓库里的 `pets/poro` 文件夹放到你的 Codex 宠物目录：

```text
~/.codex/pets/poro
```

最终目录应该长这样：

```text
~/.codex/pets/poro/pet.json
~/.codex/pets/poro/spritesheet.webp
```

然后打开 Codex Desktop，在设置里选择它：

```text
Settings -> Personalization -> Pets -> Poro
```

也可以在 Codex Desktop 的输入框里用这个命令唤醒或收起桌宠：

```text
/pet
```

### 文件说明

- `pets/poro/pet.json`: Codex 桌宠配置文件，定义桌宠 ID、显示名、描述和 spritesheet 路径。
- `pets/poro/spritesheet.webp`: 实际动画图集，包含 Poro 的全部动作帧。

### 适用场景

- 想给 Codex Desktop 添加一个自定义桌宠。
- 想要一个《英雄联盟》魄罗风格的工作陪伴小动画。
- 想参考 Codex 自定义宠物包的最小文件结构。
- 想基于现有 `pet.json` + `spritesheet.webp` 制作自己的桌宠。

## English

### Overview

`Poro` is a custom Codex Desktop pet package. It is designed as a small, friendly, low-distraction desktop companion with a League of Legends Poro-inspired silhouette and a Codex-friendly pixel-art-adjacent animation style.

The pet includes the standard Codex pet animation rows:

- `idle`
- `running-right`
- `running-left`
- `waving`
- `jumping`
- `failed`
- `waiting`
- `running`
- `review`

The final spritesheet is an RGBA WebP atlas sized `1536 x 1872`, arranged as `8` columns by `9` rows with `192 x 208` cells.

### Installation

Place the pet folder at:

```text
~/.codex/pets/poro
```

Expected files:

```text
~/.codex/pets/poro/pet.json
~/.codex/pets/poro/spritesheet.webp
```

Then open Codex Desktop and select `Poro` from:

```text
Settings -> Personalization -> Pets
```

You can also wake or hide the pet from Codex Desktop with:

```text
/pet
```

### Files

- `pets/poro/pet.json`: Pet metadata used by Codex Desktop.
- `pets/poro/spritesheet.webp`: The animated pet atlas.

## Preview And QA

The pet was generated and validated as a Codex-compatible custom pet:

- Atlas size: `1536 x 1872`
- Cell size: `192 x 208`
- Format: `WEBP RGBA`
- Unused cells: transparent
- Included package files: `pet.json` and `spritesheet.webp`

## Notice

This is a fan-made, non-commercial custom Codex pet. League of Legends and Poro are associated with Riot Games. This project is not affiliated with, sponsored by, approved by, or endorsed by Riot Games.
