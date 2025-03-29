# Screen Capture Tool / 螢幕擷取工具

<p align="center">
  <img src="icon_screen_capturer.jpg" alt="Screen Capture Tool Icon" width="200"/>
</p>

A versatile screen capture tool that supports timed captures and update-triggered screenshots. / 一個多功能的螢幕擷取工具，支援定時截圖和畫面更新觸發截圖。

## Features / 功能

- Timed screen capture / 定時截圖
- Update-triggered capture / 畫面更新時截圖
- Support for full screen and specific window capture / 支援全螢幕和指定視窗截圖
- Customizable capture intervals / 可自訂截圖間隔時間
- Automatic output folder organization by timestamp / 自動依時間戳記整理輸出資料夾

## Requirements / 需求

```bash
pip install opencv-python numpy mss PyGetWindow
```

Required Python packages / 需要的 Python 套件：
- opencv-python
- numpy
- mss
- PyGetWindow

## Installation / 安裝

1. Clone the repository / 複製專案：
```bash
git clone https://github.com/yourusername/screen-capture-tool.git
cd screen-capture-tool
```

2. Install dependencies / 安裝依賴套件：
```bash
pip install -r requirements.txt
```

## Usage / 使用方式

Run the program / 執行程式：
```bash
python main.py
```

### Menu Options / 選單選項

1. Set Interval (sec) / 設定截圖間隔時間（秒）
2. Capture Screen / 定時截圖
3. Capture on Update / 檢測更新時截圖
4. Capture on Update with Interval / 檢測更新時截圖（帶間隔）
0. Exit / 結束程式

### Output / 輸出

Screenshots are saved in the `output` folder, organized by timestamp / 截圖儲存在 `output` 資料夾中，依時間戳記分類： 

## Contributing / 貢獻指南

We welcome contributions to improve this project! Here's how you can help:

1. **Report Issues / 回報問題**
   - Report bugs or suggest features through GitHub Issues
   - 透過 GitHub Issues 回報錯誤或提出功能建議

2. **Submit Pull Requests / 提交程式碼**
   - Fork the repository / 複製專案
   - Create a new branch / 建立新分支
   - Make your changes / 進行修改
   - Submit a pull request / 提交變更

3. **Coding Guidelines / 程式碼準則**
   - Follow PEP 8 style guide / 遵循 PEP 8 程式碼風格
   - Add comments for complex logic / 為複雜邏輯加上註解
   - Include both English and Traditional Chinese comments / 包含英文和繁體中文註解

4. **Documentation / 文件**
   - Help improve documentation / 協助改善文件
   - Add examples / 新增使用範例
   - Translate content / 協助翻譯

## License / 授權條款

MIT License

Copyright (c) 2024 Screen Capture Tool

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

授權條款採用 MIT 授權，詳細內容請參閱 [LICENSE](LICENSE) 檔案。 