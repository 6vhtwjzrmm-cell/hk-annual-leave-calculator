# 香港離職員工年假計算器

## 🇭🇰 Hong Kong Annual Leave Calculator for Terminating Employees

完全符合 **香港《僱傭條例》第41章** 的離職員工年假計算工具。

### 功能

- ✅ 根據服務年期自動計算法定年假（1-2年: 7天, 3年: 8天...9年+: 14天）
- ✅ 三種法律條款自動判定：受僱 < 3個月 / 3-12個月 / ≥ 12個月
- ✅ 支持扣除已使用年假
- ✅ 上一年度 + 按比例額外 + 按比例法定 三部分詳細計算
- ✅ 繁體中文/英文雙語界面（zh-HK）

### 使用方式

直接打開: **[https://6vhtwjzrmm-cell.github.io/hk-annual-leave-calculator/](https://6vhtwjzrmm-cell.github.io/hk-annual-leave-calculator/)**

### 計算邏輯

\`\`\`
離職年假 = 
  + 法定年假（上一年度累計，基於服務年度）
  + 按比例額外年假（本年度，離職日曆年）
  + 按比例法定年假（本年度，用下一年度法定天數）
  - 已使用年假
  = 最終應得（向上取整）
\`\`\`

### 法律依據

- 香港《僱傭條例》第41章 — 有薪年假的累算及發放
- 服務年期遞增表：第1-2年7天，第3年8天...第9年或以上14天

### 部署

此為純靜態 HTML，無須伺服器，直接在 GitHub Pages 上運行。

---

Made with ❤️ | Powered by GitHub Pages
