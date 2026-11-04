# AI-Trading releases

這個倉庫只放「群益 AI 交易模組」的自動更新檔：

- `appcast.xml`：安裝檔更新清單
- `TxPanel-Setup-<版本>.exe`：最新版安裝檔（Ed25519 簽章，程式用內建公鑰驗證，簽章不符不會安裝）
- `manifest.json`、`manifest.sig`、`web/index.html`：畫面檔案更新（簽章不符不會套用）
- `invite_public.json`：邀請碼清單（只有雜湊，由程式登入時讀取）

請勿在此開發或放其他檔案。
