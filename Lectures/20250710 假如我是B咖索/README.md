# 20250710 假如我是 B 咖索

##### 【註】宣哲老師本週赴國外開會發表研究成果。

- 委請代課老師：高楊達老師現場坐鎮。
- 另請：李詠嫻助教協助同學課堂操作。

## Fooocus

> Fooocus 是一款開源的生成式人工智慧（Generative AI）圖像生成軟體，能根據文字提示快速生成圖片
> **(Text to Image, 沒有完善的中文輸入支援，建議以英文提示詞生成圖片)**。它以 Stable Diffusion XL 為核心模型，並內建多種預設參數與提示詞，讓使用者無需繁瑣設定即可獲得理想的圖像結果。

### 主要特色：

- 易於安裝與使用：Fooocus 強調「開箱即用」，不需手動調整複雜的模型參數。
- 自動提示優化：內建 GPT-2，可自動為用戶的提示詞增添細節，提高生成圖像的品質。
- 預設攝影風格：預設偏好攝影寫實風格，並提供多種風格選擇。
- Gradio 介面：採用 Gradio 為基礎的網頁介面，操作直覺。
- 高效擴展：內建 LCM（Low-rank adaptation）等常用擴展，提升生成速度。
- 進階自訂：提供進階選項，方便有經驗的用戶進行細部調整。
- API 支援：可透過 API 整合至其他軟體或自動化流程，適合開發者與企業應用。

### 開發背景：

- 由 Stanford 博士生 Lvmin Zhang 開發，他同時也是 ControlNet 的主要作者。
- Fooocus 受到 Stable Diffusion 與 Midjourney 的設計理念啟發，並強調用戶友善與自動化。

### 應用場景：

- 藝術創作、廣告設計、遊戲美術、內容生成等，任何需要快速生成高品質圖片的場合。

### Let's Go ~

1. 連到 <a href='https://github.com/lllyasviel/Fooocus' target='_new'>github Fooocus 專案的頁面</a>
2. 你可以選擇下載到自己的電腦上執行，但先決條件是家裡的電腦需要配有「強大」的 GPU 繪圖晶片，才可順利運行（最低 GPU 記憶體需求為 4GB）。

   > Fooocus presents a rethinking of image generator designs. The software is offline, open source, and free, while at the same time, similar to many online image generators like Midjourney, the manual tweaking is not needed, and users only need to focus on the prompts and images. Fooocus has also simplified the installation: between pressing "download" and generating the first image, the number of needed mouse clicks is strictly limited to less than 3. Minimal GPU memory requirement is 4GB (Nvidia).

   > Fooocus 提出了對圖片產生器設計的重新思考。此軟體為離線、開放原始碼且免費，同時與許多線上圖片產生器如 Midjourney 相似，不需要手動調整，使用者只需專注於提示與圖片即可。Fooocus 也簡化了安裝程序：從按下「下載」到產生第一張圖片之間，所需的滑鼠點擊次數被嚴格限制在 3 次以下。最低 GPU 記憶體需求為 4GB (Nvidia)。

3. 【另一種選擇】你可以像第一週的程式做法，將程式複製到你的雲端硬碟，再從你的雲端硬碟透過雲端資源來運行 Fooocus 系統。
