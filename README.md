# 計分賽程競技系統

一個基於 React + Firebase 的賽事管理平台，專為 4 人固定順序賽制設計。

## 🎯 功能特色

### 核心功能
- **固定順序賽制 (4人專用)**: AB → CD → CA → BD → BC → AD
- **即時資料庫同步**: Firebase 即時數據同步，多設備協同
- **房間管理**: 6位房間代碼，24小時有效期
- **即時積分統計**: 實時更新積分排行榜
- **多輪比賽**: 支持無限輪次，靈活結束
- **撤回功能**: 可無限次撤回比賽結果，防止誤操作

### 系統特性
- **即時性**: Firebase 即時數據同步，多設備協同
- **可擴展性**: 模組化架構，易於擴展新功能
- **用戶友好**: 直觀的操作界面，點擊即可記錄勝利
- **響應式設計**: 支持桌面和移動端設備
- **多設備支援**: 所有操作即時同步到所有連接設備

## 🏗️ 技術架構

- **前端**: React 18, React Router DOM
- **後端**: Firebase Realtime Database
- **樣式**: 原生 CSS，響應式設計
- **部署**: GitHub Pages + GitHub Actions

## 🚀 部署說明

### 在線演示
- **網站**: https://yanchen184.github.io/squash-tournament-system
- **版本**: v1.0.4

### 本地開發
```bash
# 安裝依賴
npm install

# 啟動開發服務器
npm start

# 構建生產版本
npm run build
```

### GitHub Pages 部署
項目配置了 GitHub Actions 自動部署：
- 推送到 `main` 分支自動觸發部署
- 構建產物部署到 `gh-pages` 分支
- 支持 CI=false 環境變量避免警告錯誤

## 📝 更新日誌

### v1.0.4 (2025-07-04)
- 🐛 修復點擊玩家無反應的問題
- 🔧 修正 Firebase v9 API 使用方式
- 📊 添加詳細的調試日誌
- ⚡ 優化數據庫更新性能

### v1.0.3 (2025-07-04)
- 🎨 調整排版佈局：當前對戰與對戰順序並排，積分榜在下方
- 📱 優化響應式設計
- 🖥️ 改善桌面和移動端的顯示效果

### v1.0.2 (2025-07-04)
- ❌ 移除手動加入房間功能
- ↩️ 新增撤回功能，可無限次撤回比賽結果
- 🔄 優化數據庫操作，改用批量更新
- 🎯 改善多設備同步機制

## 📄 許可證

MIT License

## 👥 貢獻

歡迎提交 Issue 和 Pull Request！

---

**版本**: v1.0.4  
**最後更新**: 2025-07-04  
**作者**: yanchen184  
**在線演示**: https://yanchen184.github.io/squash-tournament-system