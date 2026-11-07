626f6c742d63632d6167656e74我看到附图是一片深色漸層，沒有看到首頁的建築照片。首頁背景照片可能沒有載入，我可以再檢查 Hero 區塊的圖片設定。

以下是可直接複製到 GitHub 的 README.md 內容：

```markdown
# 潘信宏 Vincent Pan 個人介紹網站

朝陽科技大學資訊管理系助理教授潘信宏的個人介紹網站，呈現學歷、經歷、研究領域與聯絡方式。
設計風格採深淺色區塊交替、襯線與無襯線字體混搭，並搭配滾動淡入與微互動動畫。

參考網站：[VincentPan's Blog](https://vincentpanblog.wordpress.com/)

## 特色

- 首頁主視覺，附中英文姓名與聯絡按鈕
- 研究領域卡片，涵蓋網頁技術、機器學習、人工智慧、嵌入式系統與物聯網、智慧型運輸系統、隨意式無線網路
- 學歷時間軸與經歷列表，現職以標籤標示
- 固定導覽列，捲動時轉為半透明背景，手機版提供選單
- 響應式設計，適用手機、平板與桌面
- 中英雙語內容

## 頁面區塊

| 區塊 | 內容 |
| --- | --- |
| Hero | 主視覺、姓名、職稱與行動按鈕 |
| 關於我 | 個人簡介與基本資料 |
| 研究領域 | 六項專長與研究方向 |
| 主要學歷 | 學士、碩士、博士時間軸 |
| 經歷 | 歷年任職紀錄 |
| 聯絡我 | Email、電話與學校地址 |

## 技術棧

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Lucide React 圖示
- Google Fonts（Cormorant Garamond、Inter、Noto Sans TC、Noto Serif TC）

## 專案結構

```
├── index.html            # 入口頁、字體與 meta 設定
├── tailwind.config.js    # 色彩系統與動畫設定
├── src/
│   ├── App.tsx           # 組合各區塊
│   ├── data.ts           # 個人資料、學歷、經歷、研究領域
│   ├── index.css         # 全域樣式
│   ├── useReveal.ts      # 滾動淡入效果
│   └── components/       # 導覽列、各區塊元件
```

## 快速開始

需先安裝 [Node.js](https://nodejs.org/)（建議 18 以上版本）。

```bash
npm install        # 安裝套件
npm run dev        # 啟動開發伺服器
npm run build      # 建置正式版本
npm run preview    # 預覽正式版本
npm run lint       # 程式碼檢查
```

## 修改內容

個人資料集中在 `src/data.ts`，包含姓名、聯絡方式、學歷、經歷與研究領域，修改後即可更新網站內容。
色彩設定位於 `tailwind.config.js`。

## 圖片來源

首頁背景圖片來自 [Pexels](https://www.pexels.com/)，依其授權條款使用。

## 授權

網站程式碼可自由參考與使用。個人資料與照片之權利屬於潘信宏老師。
```
