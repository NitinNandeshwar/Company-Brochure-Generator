# Company Brochure Generator

This project is a **Company Brochure Generator** that uses LLMs (OpenAI GPT, Anthropic Claude, and Google’s models) to create short, professional brochures about companies.  
The app scrapes a company’s landing page and generates a well-structured Markdown brochure for prospective customers, investors, and recruits.

---

## 🚀 Features

- **Multi-Model Support**  
  - OpenAI GPT (`gpt-4o-mini`)  
  - Anthropic Claude (`claude-3-haiku`)  
  - Google Generative AI (optional, configurable)

- **Webpage Scraping**  
  Extracts and cleans text content from the provided company URL using **BeautifulSoup**.

- **Streaming Responses**  
  Brochure text is streamed back to the Gradio UI in real time.

- **Gradio Interface**  
  User-friendly interface for inputting company name, landing page URL, and selecting a model.

---

## 🛠️ Tech Stack

- **Python 3.9+**
- [OpenAI](https://platform.openai.com/)
- [Anthropic](https://www.anthropic.com/)
- [Google Generative AI](https://ai.google.dev/)
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/)
- [Gradio](https://gradio.app/)
- [dotenv](https://pypi.org/project/python-dotenv/)

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/company-brochure-generator.git
   cd company-brochure-generator
