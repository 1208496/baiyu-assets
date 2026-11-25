# 白雨的留灯人 · 图源

《白雨的留灯人（莉莉薇的四十九日）》角色卡的 galgame 图源仓库。卡里只存拼址规则，图都放这里。

## 目录规范

```
assets/char/{角色}/{衣装}/{表情}.webp     立绘差分
assets/bg/{地点}/{时段}.webp              背景
assets/cg/{键}.webp                       剧情 CG
assets/h/{键}.webp                        佐料 CG
assets/ph/{键}.webp                       占位（兜底）
```

- 角色键：`liliwei`
- 衣装键：`rag`（破布+项圈，1–2 章）／`dress`（亚麻连衣裙，3–4 章）／`free`（无项圈，5–6 章）
- 表情键：`fear / blank / teary / soft / shy / smile / worried / happy / blush / sadsmile / warm`

## 访问方式

- GitHub 直连：`https://raw.githubusercontent.com/1208496/baiyu-assets/refs/heads/main/{path}`
- jsDelivr：`https://testingcf.jsdelivr.net/gh/1208496/baiyu-assets@main/{path}`

前端按「角色／衣装／表情」三段拼文件名，拼不到时依次试扩展名与备用 CDN 节点。
