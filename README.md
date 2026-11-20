# 第三方支付設定

第三方支付設定後台管理介面原型頁面。

## 線上瀏覽

部署於 GitHub Pages:https://mootech-asia.github.io/Third-party-payment/

## 部署方式

推送到 `main` 分支後,GitHub Actions(`.github/workflows/deploy-pages.yml`)會自動將 `index.html` 部署到 GitHub Pages。

## 素材管理

- [跨 repo 素材目錄與製作標準](docs/ASSET_STANDARD.md)
- [素材編號、用途與規格清單](docs/ASSETS.md)
- 檢查：`python3 tools/assets.py check`；更新清單：`python3 tools/assets.py catalog`。
- 新功能製作清單：`python3 tools/assets.py brief --name 功能英文名稱`，有既有玩法範本時優先沿用範本。

## 協作與交接

Codex／Claude 接手請先讀 [CLAUDE.md](CLAUDE.md)、[AGENTS.md](AGENTS.md) 與 [HANDOFF.md](HANDOFF.md)。每次工作完成後更新交接紀錄、驗證範圍、發布狀態及待辦，避免依賴個別對話記憶。
