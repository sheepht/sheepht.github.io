# 羊姥苑工作室部落格 Sheepht's Blog

blog.sheepht.com 的 Publii 原始資料。

## 架構

```
main branch     → Publii 原始資料（input/）
gh-pages branch → Publii 發布的 HTML（自動產生）
```

## 作者

- 白羊 sexyoung — Frontend Engineer
- 黑羊 JF — Data Engineer
- 羊小編 — 工作室小編（行銷 agent 產出的文章）

## 發布流程

1. 在 Publii app 編輯文章
2. Publii 同步 → 自動推 HTML 到 `gh-pages` → blog.sheepht.com 上線
3. 備份原始資料：`git add -A && git commit -m "update" && git push origin main`
