# Actiontrauma Studio

獨立 Windows 動畫編輯器與 CLI 製作工具；此專案不隨 Actiontrauma 的 Steam Workshop 模組上傳。

- 編輯器原始碼與操作說明：`Studio/README.md`
- CLI 與格式工具：`Tools/Actiontrauma.Cli/README.md`
- 範例：`Examples/`
- 遊戲端 Lua：另於 Actiontrauma 模組專案維護。

在 `game-path.txt` 填入 Barotrauma 安裝目錄，再開啟 `Studio/Publish/Actiontrauma.Studio.exe`。設定檔不納入 Git；發布資料夾若移到其他位置，請將它放到 exe 旁。


修改格式版本、欄位或驗證上限時，請同步修改本專案的 `Studio/ProjectCodec.cs` 與模組專案的 `Lua/ActiontraumaTimeline.lua`。