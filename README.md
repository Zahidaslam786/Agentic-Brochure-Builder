# 🤖 Agentic AI Brochure Builder

An automated, intelligent workflow designed to transform a company's URL into a professional, multi-lingual brochure. This project demonstrates an **Agentic AI pattern** where a language model autonomously decides which web data is relevant to fulfill a complex task.

## 🚀 Overview
Traditional static scraping often captures "noise" like Terms of Service or Privacy policies. This system utilizes a multi-stage agentic pipeline to identify, extract, and synthesize high-value business information (Mission, Services, Culture) into a structured brochure format.

## 🛠️ The Workflow (Step-by-Step)
1. **Intelligent Discovery**: The system initializes a custom scraper to extract all raw hyperlinks from the target landing page.
2. **Autonomous Selection**: A **Llama 3.2:1b** agent analyzes the raw links and filters them to find only the most relevant pages (e.g., "About Us," "Careers").
3. **Contextual Research**: The scraper visits the selected high-value URLs to gather deep context about the company.
4. **Professional Synthesis**: The aggregated data is processed by the LLM to generate a structured brochure in English.
5. **Localization**: A final AI pass translates the content into professional Urdu, ensuring a localized impact.
6. **Real-time Delivery**: The system uses **Token Streaming** to display the brochure as it is being generated for a better user experience.

## 🔧 Technical Stack
- **Model Orchestration**: OpenAI SDK (OpenAI-compatible local endpoint).
- **LLM Infrastructure**: Ollama (Running local, free open-source models).
- **Data Engineering**: BeautifulSoup4 & Requests for web scraping.
- **Languages**: Python.

## 📈 Project Results
The following screenshots demonstrate the output of the agentic pipeline, including the researched content and the final brochures in both English and Urdu.

<div align="center">
  <img src="<img width="692" height="477" alt="image" src="https://github.com/user-attachments/assets/c60423e3-508f-4d62-9514-71ad4489fc58" /><img width="764" height="464" alt="image" src="https://github.com/user-attachments/assets/8b31ffe2-857d-41bc-8996-f85f3a8ccb8b" />

" alt="English Brochure Output" width="45%">
  <img src="<img width="711" height="420" alt="image" src="https://github.com/user-attachments/assets/e0608342-72bf-443a-9250-de1726aa7a97" /><img width="734" height="396" alt="image" src="https://github.com/user-attachments/assets/36dcd49b-25b8-49b5-be0a-5271c75f2409" />

" alt="Urdu Brochure Output" width="45%">
</div>
