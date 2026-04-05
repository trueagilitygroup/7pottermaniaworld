# 🏰 7PotterManiaWorld — 魔法世界冒險

<div align="center">

**A browser-based magical adventure game | 網頁魔法世界冒險遊戲**

[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Single_File-E34F26?logo=html5&logoColor=white)](index.html)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-success)]()
[![Responsive](https://img.shields.io/badge/Responsive-Mobile_Ready-blue)]()

[🎮 開始遊玩 Play Now](#-快速開始-quick-start) · [📖 遊戲介紹 About](#-遊戲介紹-about) · [✨ 功能特色 Features](#-功能特色-features)

</div>

---

## 📖 遊戲介紹 About

**7PotterManiaWorld** 是一款以魔法世界為主題的網頁冒險遊戲。玩家將選擇學院、學習咒語、探索城堡，在充滿魔法的世界中展開屬於自己的冒險旅程。

本遊戲為單一 HTML 檔案，無需安裝任何東西，打開瀏覽器即可遊玩。

**7PotterManiaWorld** is a browser-based adventure game set in a magical wizarding world. Players choose their house, learn spells, explore the castle, and embark on their own magical journey.

The entire game is a single HTML file — zero dependencies, zero installation. Just open and play.

---

## ✨ 功能特色 Features

### 🎮 遊戲系統 Gameplay

| 功能 Feature | 說明 Description |
|:---:|:---|
| 🏠 **四大學院** | 葛萊分多、史萊哲林、雷文克勞、赫夫帕夫，各有獨特屬性加成 |
| 📍 **13 個場景** | 大禮堂、地下城、圖書館、中庭、天文塔、萬應室、秘密通道等 |
| 🪄 **6 種咒語** | 螢光閃爍、去去武器走、破心護、乒乓去、速速前、護法咒 |
| ⚔️ **決鬥系統** | 攻擊 / 防禦 / 眩暈三種策略，基於屬性的成敗判定 |
| 📊 **屬性檢定** | 力量、智力、魅力、防禦四大屬性影響劇情走向 |
| 📈 **升級系統** | 累積經驗值升級，提升血量與魔力上限 |
| 🎒 **背包系統** | 收集藥水、魔法物品、寶物 |
| 📜 **任務追蹤** | 進行中的任務與完成進度顯示 |

### 🎨 技術特色 Technical

| 技術 Tech | 說明 Description |
|:---:|:---|
| 📄 **單檔案** | 所有 HTML / CSS / JS 打包在一個 `.html` 檔案中 |
| 🎵 **程序化音樂** | 使用 Web Audio API 即時生成魔法風格背景音樂，無外部音檔 |
| 🖼️ **SVG 場景** | 所有場景背景畫面皆由 SVG 程式碼繪製 |
| ✨ **Canvas 星空** | 動態閃爍的星空背景動畫 |
| 📱 **響應式設計** | 支援桌面、平板、手機，側邊面板自動轉為抽屜式選單 |
| 🔤 **雙語版本** | 提供繁體中文與英文版本 |
| 🚫 **零依賴** | 不需要 Node.js、npm、或任何框架 |

---

## 🚀 快速開始 Quick Start

### 方法一：直接開啟

1. 下載 `index.html`
2. 用瀏覽器打開
3. 開始冒險！

### 方法二：GitHub Pages 部署

1. Fork 或 clone 此 repo
2. 進入 repo → **Settings** → **Pages**
3. Source 選擇 **Deploy from a branch**
4. 選擇 **main** 分支，資料夾 **/ (root)**
5. 點擊 **Save**
6. 等待 1-2 分鐘，你的遊戲將上線於：

```
https://你的帳號.github.io/你的repo名稱/
```

### 方法三：其他免費託管

| 平台 | 方式 | 速度 |
|:---:|:---|:---:|
| [Netlify Drop](https://drop.netlify.app) | 拖拽上傳，免註冊 | ⚡ 30 秒 |
| [Vercel](https://vercel.com) | 拖拽或連結 GitHub | ⚡ 1 分鐘 |
| [Cloudflare Pages](https://pages.cloudflare.com) | 連結 GitHub repo | ⚡ 2 分鐘 |
| [Tiiny.host](https://tiiny.host) | 上傳單一 HTML | ⚡ 30 秒 |

---

## 🎮 遊戲攻略 Game Guide

### 學院選擇建議

| 學院 | 優勢屬性 | 遊玩風格 |
|:---:|:---:|:---|
| 🦁 葛萊分多 | 力量 9 | 擅長正面戰鬥，決鬥勝率高 |
| 🐍 史萊哲林 | 魅力 9 | 社交能力強，容易獲得幫助 |
| 🦅 雷文克勞 | 智力 10 | 解謎與魔藥調製成功率最高 |
| 🦡 赫夫帕夫 | 魅力 10 | 全方位均衡，特殊互動機會多 |

### 咒語學習路線

```
起始咒語：螢光閃爍 (Lumos) + 去去武器走 (Expelliarmus)
     │
     ├── 圖書館研習 → 破心護 (Protego)
     ├── 閱讀魔法書 → 速速前 (Accio) [需要智力 ≥ 7]
     ├── 禁書區典籍 → 乒乓去 (Stupefy)
     └── 鐘樓神秘人 → 護法咒 (Patronus) [需要魅力 ≥ 8]
```

### 小提示

- 🕯️ 學會「螢光閃爍」後再探索黑暗區域，可以發現隱藏寶藏
- 🧪 智力 ≥ 8 可以成功調製「福來福去」
- 🌙 天文塔可以休息回復血量和魔力
- 🦌 學會護法咒後，可以在天文塔向禁忌森林發送信號獲得鳳凰羽毛

---

## 📁 專案結構 Project Structure

```
7PotterManiaWorld/
├── index.html          # 遊戲主檔案（繁體中文版）
├── README.md           # 本說明文件
└── LICENSE             # MIT 授權條款 + 版權聲明
```

---

## 🛠️ 技術架構 Tech Stack

```
┌─────────────────────────────────────────┐
│              單一 HTML 檔案              │
├─────────────────────────────────────────┤
│  HTML5        結構與語義化標記           │
│  CSS3         響應式佈局 / 動畫 / 主題   │
│  Vanilla JS   遊戲邏輯 / 狀態管理       │
│  SVG          場景背景繪製               │
│  Canvas API   星空粒子動畫               │
│  Web Audio    程序化背景音樂生成         │
├─────────────────────────────────────────┤
│  Google Fonts  Noto Serif TC / Sans TC  │
│               Cinzel Decorative         │
└─────────────────────────────────────────┘
```

---

## 🌐 瀏覽器支援 Browser Support

| 瀏覽器 | 版本 | 狀態 |
|:---:|:---:|:---:|
| Chrome | 90+ | ✅ 完整支援 |
| Safari | 15+ | ✅ 完整支援 |
| Firefox | 90+ | ✅ 完整支援 |
| Edge | 90+ | ✅ 完整支援 |
| iOS Safari | 15+ | ✅ 完整支援 |
| Android Chrome | 90+ | ✅ 完整支援 |

---

## 📝 版權聲明 Copyright Notice

本專案採用 [MIT License](LICENSE) 授權。

**⚠️ 重要聲明：**

- 本專案為**粉絲自製的非商業作品**，僅供教育與娛樂用途
- 與華納兄弟娛樂公司、J.K. 羅琳或任何相關機構**無關**，亦**未獲得其授權**
- 所有與哈利波特相關的名稱、角色及引用均為其各自所有者的商標
- 本專案**未使用任何受版權保護的素材**：
  - 🖼️ 所有視覺藝術由 SVG 程式碼生成
  - 🎵 所有音樂由 Web Audio API 程序化生成
  - 🔤 使用開源字型（Google Fonts）

**⚠️ Important Notice:**

- This is a **fan-made, non-commercial** project for educational and entertainment purposes only
- **Not affiliated with** or endorsed by Warner Bros. Entertainment, J.K. Rowling, or any related entities
- All Harry Potter-related names and references are trademarks of their respective owners
- **No copyrighted assets** are used in this project

---

## 🤝 貢獻 Contributing

歡迎提交 Issue 或 Pull Request！

Contributions are welcome! Feel free to open issues or submit pull requests.

---

<div align="center">

**Made with 🪄 magic and ☕ coffee**

*「是我們的選擇，而非我們的能力，決定了我們是什麼樣的人。」*

</div>
