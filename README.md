# 🤖 Agentic AI Brochure Builder

An automated, intelligent workflow designed to transform a company's URL into a professional, multi-lingual brochure. This project demonstrates an **Agentic AI pattern** where a language model autonomously decides which web data is relevant to fulfill a complex task.

## 🚀 Overview
Traditional static scraping often captures "noise." This system utilizes a multi-stage agentic pipeline to identify, extract, and synthesize high-value business information (Mission, Services, Culture) into a structured brochure format.

## 🛠️ The Workflow (Step-by-Step)
1. **Intelligent Discovery**: Extracts raw hyperlinks from the target landing page using BeautifulSoup.
2. **Autonomous Selection**: A **Llama 3.2:1b** agent analyzes and filters links to find high-value pages like "About Us" or "Careers".
3. **Contextual Research**: The scraper visits selected URLs to gather deep business context.
4. **Professional Synthesis**: Data is processed to generate a structured brochure in English.
5. **Localization**: A final AI pass translates the content into professional Urdu.
6. **Real-time Delivery**: Uses **Token Streaming** to display the brochure dynamically.

## 🔧 Technical Stack
- **Model Orchestration**: OpenAI SDK (OpenAI-compatible local endpoint).
- **LLM Infrastructure**: Ollama (Running local, free open-source models like Llama 3.2:1b).
- **Data Engineering**: BeautifulSoup4 & Requests.

## 📈 Project Results

### English Brochure Output
<div align="center">
  <img src="https://github.com/user-attachments/assets/c60423e3-508f-4d62-9514-71ad4489fc58" width="48%" />
  <img src="https://github.com/user-attachments/assets/8b31ffe2-857d-41bc-8996-f85f3a8ccb8b" width="48%" />
</div>

### Urdu Brochure Output
<div align="center">
  <img src="https://github.com/user-attachments/assets/e0608342-72bf-443a-9250-de1726aa7a97" width="48%" />
  <img src="https://github.com/user-attachments/assets/36dcd49b-25b8-49b5-be0a-5271c75f2409" width="48%" />
</div>

