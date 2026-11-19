# 亞太越野賽事總覽 APAC Trail Races

靜態網站（單一 `index.html` + `data.js` + `assets/`），hash routing：
`#/` 亞太首頁 → `#/region/<id>` 地區頁 → `#/event/chiangmai-utmb` 賽事總覽 → `#/race/<slug>` 賽事頁。

所有頁面由同一套模板 + 結構化資料生成；改模板一次，全部頁面跟隨。
資料核實自 UTMB 官方賽事頁、官方時間表及官方 GPX（最後整理：2026 年 11 月）。

GitHub Pages: Settings → Pages → Deploy from branch `main` / root。
