# 2-gradio-Stable_Diffusion_V1_5_Test
20260519homework
# AI Image Generator with Stable Diffusion & Gradio

這是一個基於 Jupyter Notebook 開發的 AI 圖像生成專案。本專案利用 Hugging Face 的 `diffusers` 庫載入 Stable Diffusion 權重，並透過 `Gradio` 快速搭建一個可互動的網頁介面，讓使用者輸入文字提示詞（Prompt）即可即時生成對應的 AI 繪圖圖像。

## 🚀 功能特點

- **文字生成圖片 (Text-to-Image)**：輸入任意英文描述，即可透過深度學習模型生成高品質影像。
- **直觀網頁 UI**：整合 Gradio 框架，提供簡潔的使用者輸入框與結果展示區。
- **一鍵分享**：啟動時自動生成公共分享連結（Share Link），方便遠端測試與展示。
- **GPU 加速支援**：程式碼預設配置於 CUDA 環境執行，提供流暢的生成體驗。

## 🛠️ 核心技術與模型

- **深度學習模型**：`CompVis/stable-diffusion-v1-4` (Hugging Face)
- **前端互動框架**：`Gradio`
- **主要後端依賴**：`Diffusers`、`Transformers`、`Accelerate`、`PyTorch`

## 📦 環境安裝與需求

本專案建議在支援 GPU（如 NVIDIA T4、P100 等）的環境（如 Google Colab 或本地 CUDA 環境）中執行。

請在終端機或環境中安裝以下必要的 Python 套件：

```bash
pip install gradio diffusers accelerate torch transformers
