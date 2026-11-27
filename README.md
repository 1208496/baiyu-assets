# 红瞳的莉莉亚娜 · 图片源

《红瞳的莉莉亚娜》角色卡用的图片仓库。卡里只存拼址规则，图都在这里；**新图放到对应路径即可生效**，不需要重新打包。

## 目录

```
assets/
├─ char/liliana/{m|s}/{maid|shirt|knit|nude}.webp   角色立绘（m / s 为两种状态）
├─ char/liliana/{m|s}/{maid|shirt|knit|nude}/       互动差分（head / breast / hip，maid 另有 skirt）
├─ h/{m|s}/{scene}_{1|2}.webp                       场景插图（每个场景 2 张，编号 1 / 2）
└─ bg/{door|room|bedroom|kitchen|porch}.webp        场景背景（地点基准图）
   bg/{room_night|bedroom_day|bedroom_mirror|bedroom_night|bedroom_morning|porch_dawn}.webp  场景背景（时段/场景变体）
   bg/default.webp                                  兜底背景
```

## 规格

- 立绘 / 差分：1248×1824，透明背景 WebP
- 背景：1280×720，16:9，WebP
- 文件名全 ASCII，小写下划线
- 角色外观与配色已定稿，具体规格见项目内配置，不在本仓库复述

## 访问

- GitHub：`https://raw.githubusercontent.com/1208496/baiyu-assets/refs/heads/main/{path}`
- jsDelivr：`https://testingcf.jsdelivr.net/gh/1208496/baiyu-assets@main/{path}`

`_legacy/` 及早期目录（`char/liliwei/`、旧 `bg/{地点}/{时段}/`、`h/h01_*` 等）为历史存档，当前不再引用。
