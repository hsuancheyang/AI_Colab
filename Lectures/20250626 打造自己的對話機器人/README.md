# 2025-06-23

## 課程大綱：
介紹近年火紅的 `生成式人工智慧` 與 `NLP（Ｎatural Language Processing）` 的原理以及所遭遇的問題。電腦該如何理解自然語言的意涵，以及自然語言處理包括的多種步驟：認知、理解、生成等部分。
### 自然語言處理研究遭遇的問題：
* 單詞的邊界界定<br>
* 詞義的消歧<br>
* 句法的模糊性<br>
* 瑕疵或不規範的輸入<br>
* 語言行為與真實意圖的推論<br>
### 現代自然語言處理研究的發展趨勢：
* 語料庫建置和語料庫語言學，透過機器學習處理成為自然語言處理的主要選擇。<br>
* 透過統計方法來取得`最可能`的答案。<br>
* 淺層處理與深層處理並重，統計與規則方法並重，混合式的系統。<br>
* 文字向量、語句向量與自我關注(Self-Attention)

得力於晶片技術以及運算能力的大幅增長，近年的人工智慧發展得到了突飛猛進的進程，隨GPT大語言模型的相繼問世，自然語言處理的發展重點從`自然語言理解`轉向了`自然語言生成`。


## 第一次作業
1. 挑選三個大語言模型
2. 利用LM Studio 
> - <a href="https://lmstudio.ai/" target="_blank" rel="noopener noreferrer">下載 LM Studio</a>
> - <a href="https://the-walking-fish.com/p/lmstudio/" target="_blank" rel="noopener noreferrer">LM Studio教學</a>
3. 或是 Colab
> - 複製 <a href="https://github.com/hsuancheyang/AI_Colab/blob/main/20250626%E6%89%93%E9%80%A0%E8%87%AA%E5%B7%B1%E7%9A%84%E5%B0%8D%E8%A9%B1%E6%A9%9F%E5%99%A8%E4%BA%BA.ipynb">老師的程式</a> 到你的雲端硬碟再修改與執行。
![image](/images/2025-06-30 09.16.25.png)
>> Open in Colab
4. 詢問「同一個問題」，透過調整：
> - 人設 System
> - 溫度 Tempture
> - Top-P 值
> - Top-K 值
 
> 比較這三個大語言模型的回答最深得你心？並告訴我原因？
