# 《房間戰線》工具箱 — RoomFront

30 Minutes Missions（30MM）粉絲自製桌上戰棋的兩件配套工具，皆為**單一 HTML 檔、純前端、手機可用、不連線**。

## 線上使用

👉 **https://darkbearlab.github.io/RoomFront/**

| 頁面 | 說明 |
|---|---|
| [`index.html`](index.html) | 入口頁，連到下面兩個工具 |
| [`builder.html`](builder.html) | **機體卡產生器**：拖拉編組、即時計價、列印 A4 機體卡、複製分享連結 |
| [`helper.html`](helper.html) | **對戰 Helper**：《玩家操作 SOP》的可執行版，算骰數門檻、維護我方熱／結構／時間軌、攻守結算交握 |

### 使用流程
1. 在 **產生器** 編好隊伍。
2. 按 **「⚔ 以此配置開戰」**（或「複製分享連結」）。
3. **Helper** 會用網址 `#f=` 自動載入整隊機體，直接開打。

Helper 只管「你這隊」——不管對手狀態、不管主導權、不連線；對手那邊由桌上口頭協調。

## 設計文件（spec）

- `_對戰helper規格_最新.md` — Helper 功能規格
- `_玩家操作SOP_最新.md` — 玩家操作流程（Helper 的行為藍本）
- `_完整規則_最新.md` — 完整規則
- `_武器表_最新.md` — 武器與機體數值表

## 部署（GitHub Pages）

Settings → Pages → Build and deployment → Source 選 **Deploy from a branch** → Branch `main` / `(root)` → Save。
之後 `main` 的每次 push 都會自動重新發佈到 https://darkbearlab.github.io/RoomFront/ 。

## 授權聲明

本作為粉絲自製規則，與 BANDAI SPIRITS 無關。30 Minutes Missions、30MM 為其所有者之商標。非商業用途。
