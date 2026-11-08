# Kevin 的 Claude Code 互動學院

用動畫、模擬器和逐步練習學 Claude Code 的繁體中文（台灣）學習網站。內容整理自 [claude-code-zh-tw](https://github.com/kevin801221/claude-code-zh-tw) 與 Claude Code 官方文件。

**線上版：** https://kevin801221.github.io/claude-code-academy/

## 內容

| 頁面 | 說明 |
|------|------|
| [`index.html`](index.html) | 學院首頁：學習路線（入門 → 進階 → 高手）、全站學習進度、模組導覽、名詞速查 |
| [`memory.html`](memory.html) | 模組 01：CLAUDE.md 的載入機制，含 monorepo 模擬器、分類遊戲、測驗 |
| [`agent-teams.html`](agent-teams.html) | 模組 02：Agent Teams 實作，含子代理對照、Command → Agent → Skill 管線模擬、團隊協作動畫 |
| [`goal.html`](goal.html) | 模組 03：`/goal` 實作，含迴圈動畫、目標模擬器、`/goal`／`/loop`／auto 模式比較、社群 prompt 技巧 |
| [`demos.html`](demos.html) | 功能演示館：權限模式、Checkpoints、脈絡管理、Session 管理、Skills、Hooks、Subagents、MCP、Plugins、Worktrees、Headless、`/goal`、`/loop` 共 13 個功能的逐步動畫，看完會記錄進度 |
| [`tips.html`](tips.html) | 心法集：13 份來源、124 條實戰心法、494 個步驟，每一步都有終端機／編輯器模擬畫面；有「新手先看這 10 條」、搜尋、主題篩選與學習進度 |
| [`404.html`](404.html) | 找不到頁面時的導引頁（GitHub Pages 用） |
| [`workflows.html`](workflows.html) | 方法論館：Matt Pocock skills、Superpowers、Compound Engineering、GSD、Spec Kit、BMAD 六套工作流的流程鏈動畫、各階段終端機模擬、跨方法比較，以及三題選出適合你的方法 |

## 使用方式

- **線上看：** 打開上面的 GitHub Pages 網址。
- **離線看：** 下載整個 repo，直接用瀏覽器開啟 `index.html`。
- **找東西：** 任何頁面按 ⌘K（Windows 按 Ctrl+K）或右上角的放大鏡，就能搜尋全站的心法、功能、方法論與名詞。

每個頁面都是單一 HTML 檔，CSS 與 JavaScript 都寫在檔案裡，不需要建置步驟，也不載入任何外部資源。學習進度與深淺色設定只存在你自己瀏覽器的 localStorage。

## 說明

- 動畫、模擬器的終端機輸出與範例資料為示意；指令、檔案路徑與設定依 2026 年 11 月的 Claude Code 官方文件整理。Claude Code 更新頻繁，細節請以[官方文件](https://code.claude.com/docs)為準。
- 心法集的步驟由原文整理改寫，每條都附原文出處；少數收尾步驟是依原文意思補上的實作建議。
- Memory 與 Agent Teams 模組另外附上「官方文件補充」，標出社群文章與最新官方文件不同的地方。

## 資料來源與授權

- [kevin801221/claude-code-zh-tw](https://github.com/kevin801221/claude-code-zh-tw)：繁體中文版（MIT）
- [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)：英文原作（MIT）
- [Claude Code 官方文件](https://code.claude.com/docs)
- 方法論館的各方法原始 repo：[mattpocock/skills](https://github.com/mattpocock/skills)、[obra/superpowers](https://github.com/obra/superpowers)、[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)、[open-gsd/gsd-core](https://github.com/open-gsd/gsd-core)、[github/spec-kit](https://github.com/github/spec-kit)、[bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)

本 repo 以 MIT 授權釋出，並保留上游作品的著作權與授權聲明，詳見 [`LICENSE`](LICENSE)。
