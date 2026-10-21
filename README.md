# Math Survivors - Cursor + Godot AI 設計文件包

將此資料夾中的所有 .md 檔案下載後，放到你的 Godot 專案根目錄。

## 使用方式
1. 下載或 clone 此 repo。
2. 把所有 .md 檔放進 Godot 專案根目錄。
3. 在 Cursor 中開啟該專案。
4. 把下方「總指令」完整貼給 Cursor（建議使用 Agent / Composer 模式）。

## 總指令（複製貼上）

請完整閱讀專案中的以下檔案：
- 00_MASTER_GOAL.md
- 01_GAME_DESIGN.md
- 02_ART_AND_FEEL.md
- 03_TECH_ARCHITECTURE.md
- 04_IMPLEMENTATION_PLAN.md

你的任務是依照這些文件，使用 Godot AI 外掛（MCP 工具）在編輯器中直接開發這款遊戲，目標是高完成度可玩版本。

執行規則：
1. 嚴格按照 04_IMPLEMENTATION_PLAN.md 的階段順序進行。
2. 優先使用 Godot AI 工具直接在編輯器建立場景、節點、腳本與資源，不要只輸出程式碼讓我手動貼。
3. 視覺依照 02_ART_AND_FEEL.md，先用精緻幾何 + 發光 + 粒子做出高質感。
4. 每完成一個主要階段：
   - 存檔
   - 簡短回報完成了什麼
   - 描述目前主要場景結構
   - 然後自動繼續下一階段
5. 遇到需要取捨時，優先保證核心循環可玩、穩定、有手感。
6. 程式盡量資料驅動，方便擴充。
7. 注意效能與物件池。

現在開始執行階段 1，並持續推進直到完成階段 4 或達到明確可玩的高完成度狀態。
開始前先確認目前 Godot 編輯器連線正常且場景為空。