# Monthly Budget Tracker

## English

### Overview
`Monthly Budget Tracker2.html` is an enhanced version of the monthly budget tracker with currency switching and built-in category presets.

### Features
- Add or update budget categories with custom amounts
- Choose from common category presets such as Food, Rent, Travel, and Savings
- Switch between multiple currencies including USD, SGD, TWD, EUR, GBP, JPY, CNY, and HKD
- Add expenses with date, category, description, and amount
- View total budget, total spending, and remaining balance
- Get warnings when a category reaches 90% of its budget
- Get alerts when a category or total monthly budget goes over budget
- Review expense history and delete individual expense entries
- Visualize spending with a pie chart using Chart.js
- Save data automatically with `localStorage`

### How to Use
1. Open `Monthly Budget Tracker2.html` in a web browser.
2. Choose your preferred currency in the settings area.
3. Add a category manually or select one from the preset list.
4. Enter a budget amount and click `Add / Update Category`.
5. Add expenses and monitor the dashboard, warnings, and chart.
6. Use `Reset All Data` if you want to clear the saved budget and expense data.

### Notes
- This project runs fully on the client side.
- Saved data is stored in the current browser only.
- Currency display changes the formatting shown in the UI; it does not convert previously entered values.
- The chart library is loaded from the Chart.js CDN, so internet access may be needed when opening the page for the first time.

## 繁體中文

### 專案介紹
`Monthly Budget Tracker2.html` 是加強版的每月預算追蹤工具，額外提供幣別切換與常用分類預設選項。

### 功能特色
- 新增或更新自訂分類預算
- 可使用常見分類預設，例如 Food、Rent、Travel、Savings
- 支援多種幣別切換，包含 USD、SGD、TWD、EUR、GBP、JPY、CNY、HKD
- 新增支出資料，包含日期、分類、說明與金額
- 顯示總預算、總支出與剩餘金額
- 當分類使用達到 90% 預算時顯示提醒
- 當分類或整體月預算超支時顯示警告
- 檢視支出紀錄並刪除單筆資料
- 使用 Chart.js 圓餅圖呈現支出分布
- 透過 `localStorage` 自動儲存資料

### 使用方式
1. 在瀏覽器中開啟 `Monthly Budget Tracker2.html`。
2. 先在設定區選擇想要使用的幣別。
3. 可手動輸入分類，或從預設分類清單中挑選。
4. 輸入預算金額後，按下 `Add / Update Category`。
5. 新增支出資料後，即可查看儀表板、警告與圖表。
6. 若要清除已儲存的預算與支出資料，可使用 `Reset All Data`。

### 注意事項
- 此專案完全在前端執行。
- 資料只會儲存在目前使用的瀏覽器中。
- 幣別切換只會改變介面上的顯示格式，不會自動換算先前輸入的金額。
- 圖表套件透過 Chart.js CDN 載入，首次開啟頁面時可能需要網路連線。
