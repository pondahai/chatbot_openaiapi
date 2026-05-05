# chatbot_openaiapi

這個專案包含多個版本的 OpenAI 相容 API 網頁對話程式，可以透過這些連結測試:  
* [最新整合版 (Gemini 3.1) - 推薦使用](https://pondahai.github.io/chatbot/chat_openaiapi_gemini_3_1.html)
* [GPT-4.1 改良版](https://pondahai.github.io/chatbot/chat_openaiapi_gpt_4_1.html)
* [Qwen 2.5 原始完成版](https://pondahai.github.io/chatbot/chat_openaiapi_qwen2_5.html)

![螢幕擷取畫面 2024-11-15 220155](https://github.com/user-attachments/assets/c775f740-2af8-4f7e-8057-6ff9b1c45c2f)  
![image](https://github.com/user-attachments/assets/689c4f02-0759-41be-b423-3b279f0c13c5)  
  
## 程式起源與演進
這個程式一開始是我在 huggingface 上面使用 [千問 2.5 (Qwen 2.5 Coder)](https://huggingface.co/spaces/Qwen/Qwen2.5-Coder-Artifacts) 以對話方式生成的 AI 聊天表皮程式。
這個程式透過設定 API 網址與金鑰，可以與大語言模型進行對話，並且所有變數與對話歷史紀錄都會存放在瀏覽器的本機儲存庫 (localStorage) 中，每次重新打開這個網頁程式就會自動載入。
  
### 版本說明：
* **chat_openaiapi_gemini_3_1.html** (最新版本)
  由 Gemini 協助整合了前兩版的優點。保留了 GPT-4 版本的精美 UI 設計與 Markdown/純文字複製按鈕，並完美融合了 Qwen 版本的 MathJax 數學公式渲染功能（可從設定選單中自由開啟/關閉）。
* **chat_openaiapi_gpt_4_1.html**
  後來用 GPT-4 接著改良的程式。擁有較為現代化的介面（漸層背景、陰影效果等）並新增了一鍵複製訊息的功能。
* **chat_openaiapi_qwen2_5.html**
  千問 2.5 協助開發的最後完成版本。包含了基礎的聊天功能、圖片上傳辨識、並支援 Mermaid 與初步的 MathJax 數學公式渲染。
* **test.html ~ test15.html**
  開發過程中的半成品程式與測試紀錄。