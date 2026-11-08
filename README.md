# Kevin 的 Claude Code 互動學院

用動畫、模擬器和逐步練習學 Claude Code 的繁體中文（台灣）學習網站。內容整理自 [claude-code-zh-tw](https://github.com/kevin801221/claude-code-zh-tw) 與 Claude Code 官方文件。

**線上版：** https://kevin801221.github.io/claude-code-academy/

## 內容

| 頁面 | 說明 |
|------|------|
| [`index.html`](index.html) | 學院首頁：八站學習路線（完成會打勾、標出下一站）、全站學習進度、今日心法、學習資源、模組導覽、名詞速查、關於與更新紀錄 |
| [`start.html`](start.html) | 新手教學：Day 0 在 macOS／Windows／Linux 安裝與登入（依官方文件），Day 1 三堂課學會 prompting、代理與 Skills；每一步都有終端機模擬，完成會記錄進度 |
| [`memory.html`](memory.html) | 模組 01：CLAUDE.md 的載入機制，含 monorepo 模擬器、分類遊戲、測驗與官方文件補充 |
| [`agent-teams.html`](agent-teams.html) | 模組 02：Agent Teams 實作，含子代理對照、Command → Agent → Skill 管線模擬、團隊協作動畫與官方文件補充 |
| [`goal.html`](goal.html) | 模組 03：`/goal` 實作，含迴圈動畫、目標模擬器、`/goal`／`/loop`／auto 模式比較、社群 prompt 技巧 |
| [`demos.html`](demos.html) | 功能演示館：權限模式、Checkpoints、脈絡管理、Session 管理、Skills、Hooks、Subagents、MCP、Plugins、Worktrees、Headless、`/goal`、`/loop` 共 13 個功能的逐步動畫，看完會記錄進度 |
| [`tips.html`](tips.html) | 心法集：24 份來源、211 條實戰心法、846 個步驟，每一步都有終端機／編輯器模擬畫面；有「新手先看這 10 條」、搜尋、主題篩選、收藏與學習進度 |
| [`workflows.html`](workflows.html) | 方法論館：Matt Pocock skills、Superpowers、Compound Engineering、GSD、Spec Kit、BMAD 六套工作流的流程鏈動畫、各階段終端機模擬、跨方法比較，以及三題選出適合你的方法 |
| [`reference.html`](reference.html) | 參考手冊：96 個斜線指令、70 個啟動旗標／子命令／環境變數、56 個 frontmatter 欄位、內建 Skills 與代理類型；可搜尋、篩選、一鍵複製，每筆都能用網址直接分享 |
| [`exam.html`](exam.html) | 結業測驗：從 57 題題庫隨機抽 20 題，作答後馬上看解析；答對 80% 以上可以產生並下載寫上名字的結業證書 |
| [`404.html`](404.html) | 找不到頁面時的導引頁（GitHub Pages 用） |

其他檔案：`search-index.js`（全站搜尋索引與今日心法）、`og.png`（分享預覽圖）、`sitemap.xml`。

## 使用方式

- **線上看：** 打開上面的 GitHub Pages 網址。
- **離線看：** 下載整個 repo，直接用瀏覽器開啟 `index.html`。
- **找東西：** 任何頁面按 ⌘K（Windows 按 Ctrl+K）或右上角的放大鏡，就能搜尋全站的心法、功能、方法論、指令與名詞。
- **鍵盤：** 新手教學與心法可以用 ← → 切換步驟；每頁開頭都有「跳到主要內容」連結。

每個頁面都是單一 HTML 檔，CSS 與 JavaScript 都寫在檔案裡，不需要建置步驟，也不載入任何第三方資源；只有全站搜尋索引放在共用的 `search-index.js`。學習進度、收藏、測驗成績與深淺色設定只存在你自己瀏覽器的 localStorage。

## 說明

- 動畫、模擬器的終端機輸出與範例資料為示意；指令、檔案路徑與設定依 2026 年 11 月的 Claude Code 官方文件整理。Claude Code 更新頻繁，細節請以[官方文件](https://code.claude.com/docs)為準。
- 心法集的步驟由原文整理改寫，每條都附原文出處；少數收尾步驟是依原文意思補上的實作建議。原文提到的指令若在新版改名（例如 `/vim` 改到 `/config`、`/extra-usage` 改名 `/usage-credits`），步驟裡會註明。
- 參考手冊每一區都標出資料日期：斜線指令與 frontmatter 為 2026-11（Claude Code v2.1.318），啟動旗標整理自 2026-03 的文件。
- Memory 與 Agent Teams 模組另外附上「官方文件補充」，標出社群文章與最新官方文件不同的地方。

## 資料來源與授權

- [kevin801221/claude-code-zh-tw](https://github.com/kevin801221/claude-code-zh-tw)：繁體中文版（MIT）
- [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)：英文原作（MIT）
- [Claude Code 官方文件](https://code.claude.com/docs)
- 方法論館的各方法原始 repo：[mattpocock/skills](https://github.com/mattpocock/skills)、[obra/superpowers](https://github.com/obra/superpowers)、[EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)、[open-gsd/gsd-core](https://github.com/open-gsd/gsd-core)、[github/spec-kit](https://github.com/github/spec-kit)、[bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)

本 repo 以 MIT 授權釋出，並保留上游作品的著作權與授權聲明，詳見 [`LICENSE`](LICENSE)。
