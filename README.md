# Dowsing Chart | 靈擺測量圖

[English](#english) | [中文繁體](#中文繁體)

![Dowsing Chart Preview](https://raw.githubusercontent.com/hongdartw/dowsing_chart/main/preview.png)

<a name="english"></a>
## English

### Project Introduction
This project is a front-end interactive web page that allows users to freely input a list of text items and dynamically generate a three-layer semi-circular fan chart based on the number of input items. Each fan sector displays corresponding text, creating a concise and visual representation of the list, suitable for dowsing measurements or energy detection scenarios.

### Features
- Free input of multiple text items, one item per line.
- Three-layer concentric semi-circle structure:
  - Outer layer: Displays user-input items, automatically divided based on the number of items.
  - Middle layer: Fixed display of five evaluation levels (Critical, Poor, Fair, Good, Excellent).
  - Inner layer: Displays numerical range (-10 to +10).
- Each fan sector displays corresponding text, with text layout conforming to the fan shape.
- Automatic font size adjustment based on text length to ensure readability.
- Button for real-time chart updates.
- Pure front-end implementation, no dependency on external libraries.
- Apple-style clean and aesthetic design, supporting responsive layout.

### Usage Instructions
1. Enter multiple lines of text in the input box, with each line representing one item.
2. Click the "Update Chart" button, and the three-layer semi-circular fan chart will be displayed in the center of the screen.
3. You can modify the text and update the chart at any time.
4. A set of example items (body parts, emotional states, etc.) is included by default.

### Technical Details
- Uses SVG to draw the three-layer concentric semi-circular fan chart.
- JavaScript dynamically calculates the angle of each fan sector and renders it.
- Text is arranged radially to ensure readability.
- CSS implements modern UI design, including gradient buttons and shadow effects.
- Responsive design, adapting to different screen sizes.

### Future Improvements
- Support for diverse or customizable fan sector colors.
- Add mouse interaction tooltips.
- Provide fan sector click events and selection effects.
- Add pointer animation effects.
- Provide save/export chart functionality.

---

<a name="中文繁體"></a>
## 中文繁體

### 專案介紹
本專案是一個前端互動網頁，允許使用者自由輸入一組文字清單，並根據輸入項目數量動態繪製三層半圓形扇形圖。每個扇形區塊會顯示對應的文字，實現簡潔且可視化的清單展示，適合用於靈擺測量或能量檢測等場景。

### 功能特色
- 自由輸入多項文字清單，每行一項。
- 三層同心半圓結構：
  - 最外層：顯示使用者輸入的項目，根據項目數量自動等分。
  - 中間層：固定顯示五個評估等級（Critical、Poor、Fair、Good、Excellent）。
  - 最內層：顯示數值範圍（-10到+10）。
- 每個扇形區塊顯示對應的文字，文字排版符合扇形形狀。
- 根據文字長度自動調整字體大小，確保可讀性。
- 按鈕即時更新圖形。
- 純前端實現，不依賴任何外部函式庫。
- Apple風格的簡潔美觀設計，支援響應式佈局。

### 使用說明
1. 在文字輸入框中輸入多行文字，每行為一個項目。
2. 點擊「更新圖形」按鈕，畫面中央會顯示對應的三層半圓扇形圖。
3. 可隨時修改文字並重新更新圖形。
4. 預設已包含一組示例項目（身體部位、情緒狀態等）。

### 技術細節
- 使用 SVG 繪製三層同心半圓扇形圖。
- JavaScript 動態計算每個扇形的角度並繪製。
- 文字沿著徑向排列，確保可讀性。
- CSS 實現現代化的 UI 設計，包括漸變按鈕和陰影效果。
- 響應式設計，適應不同螢幕尺寸。

### 未來改進
- 支援扇形顏色多樣化或自定義。
- 增加滑鼠互動提示文字。
- 提供扇形點擊事件和選中效果。
- 增加指針動畫效果。
- 提供保存/匯出圖形功能。

---

## License
MIT License © 2025 hongdartw
