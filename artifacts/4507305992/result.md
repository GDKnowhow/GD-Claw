# 更換「小龍蝦」名稱 — 步驟與驗證

1) 決定新名稱（例：小海螯）。

2) 在倉庫中搜尋並替換所有「小龍蝦」出現處：README、AGENTS.md、issue 範本、文件、UI 文案、CI/workflow、腳本與程式註解。
   - 建議先建立分支（e.g. rename-xiaolongxia），以小步驟修改並建立 PR。
   - 本地搜尋： `git grep -n "小龍蝦"`

3) 更新會受影響的程式邏輯（例如自動產生分支/issue 名稱的程式），確保變更不破壞命名規則。

4) 執行測試與 CI，人工檢視文件頁面與範本顯示是否正確。

5) 開 PR 說明變更清單，請同事 review，合併後通知團隊並更新任何外部文件或整合設定。

驗證清單：
- README/AGENTS.md 顯示新名稱。
- issue 範本與 bot 回覆使用新名稱。
- CI 與自動化流程無錯誤。

產出檔案位置：
artifacts/4507305992/result.md

可下載（raw）：
https://github.com/GD-Claw/GD-Claw/blob/main/artifacts/4507305992/result.md?raw=true

完成：是。