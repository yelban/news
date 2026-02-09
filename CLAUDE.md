# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

AI 產業動態聚合平台，生成多主題的結構化新聞掃描日報（Markdown 格式）。報告以繁體中文撰寫，聚合來自 Reddit、Hacker News、HuggingFace、科技新報等數十個資訊來源的內容。

## Repository Structure

```
reports/
├── tech.md              # 全網技術新聞掃描（35+ 來源）
├── ai_university.md     # AI 轉型大學日報（43+ 來源）
├── perovskite.md        # 鈣鈦礦產業動態（太陽能電池）
└── raw/                 # 時間戳記的原始掃描資料
    └── {topic}_scan_{YYYYMMDD}_{HHMM}.md
```

- `reports/*.md` — 整理後的最終報告（無時間戳記檔名）
- `reports/raw/` — 原始掃描，檔名含時間戳記，用於保留歷史版本

## Report Format Convention

每份報告遵循固定結構：

1. **頭部**：封面圖、標題、生成時間、資訊來源數量
2. **頭條精選**：Top N 按熱度排序，含標題連結、來源、熱度指標、核心觀點
3. **分層分析**（L1–L6）：能源基礎設施 → 晶片算力 → 雲端平台 → AI 模型研究 → 商業應用 → 人才生產力
4. **表格彙整**：`| 中文摘要 | 來源 | 時間 | 標題連結 |`

## Deployment

- GitHub repo: `yelban/news`
- 預計使用 GitHub Pages 部署，`404.html` 可作為 SPA fallback（所有未匹配路徑都會顯示 404.html）

## Notes

- 目前無建構工具、無 CI/CD、無套件管理
- 報告生成流程為外部工具產出，本 repo 僅存放結果
