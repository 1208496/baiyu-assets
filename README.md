# 白雨的留灯人 · 图源

《白雨的留灯人（莉莉薇的四十九日）》角色卡的 galgame 图源仓库。**卡里只存拼址规则，图全在这里。**

## 目录（一条资源一类，不混放）

```
assets/
├─ char/liliwei/{衣装}/{表情}.webp    立绘差分（衣装：rag / dress / free）
├─ bg/{地点}/{时段}.webp              背景（地点：shop/attic/porch/street/room；时段：morning/afternoon/night/rain）
├─ cg/{键}.webp                       剧情 CG（待出）
├─ h/{键}.webp                        佐料 CG（h01_m_* / h02_c_* 各 insert/climax/after）
└─ ph/{char,bg,cg,h}/{键}.webp        占位图（兜底，永不进正式引用）
_legacy/char/                         旧扁平命名（sp_rag_fear.webp 那批），仅留档，不引用
manifest.json                         素材清单（id / 文件 / 尺寸 / 来源 / seed）
```

## 命名

- 角色 `liliwei`；衣装 `rag`（1–2 章）／`dress`（3–4 章）／`free`（5–6 章）
- 表情：`fear / blank / teary / soft / shy / smile / worried / happy / blush / sadsmile / warm`
- 立绘一律 **1152×1728 透明 WebP**；背景 **1920×1080**；H 图 **832×1216**
- 全部 ASCII 文件名；中文只出现在剧本标签里

## 访问

- GitHub 直连：`https://raw.githubusercontent.com/1208496/baiyu-assets/refs/heads/main/{path}`
- jsDelivr：`https://testingcf.jsdelivr.net/gh/1208496/baiyu-assets@main/{path}`
  （另有 fastly / gcore / jsd.onmicrosoft.cn / b-cdn / jsdmirror 五条备用）

前端按「角色／衣装／表情」三段拼文件名，拼不到时依次试扩展名（webp→png→jpg→jpeg）与备用 CDN 节点；单段名会自动落到 `assets/ph/{类别}/`。
