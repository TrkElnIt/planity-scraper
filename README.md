# 💇‍♀️ Planity Scraper

A Python tool that scrapes beauty salon listings from [Planity.com](https://www.planity.com/) across Paris arrondissements.  
It extracts business names, addresses, ratings, and other key data, with optional LLM processing to clean noisy HTML blocks.

---

## ✅ What It Does

- Navigates Planity's UI to search by arrondissement (75001–75020)
- Extracts salon name, rating, address, and basic metadata
- Handles pagination through result pages
- Uses an LLM (Mistral or GPT-4) to parse complex inner content
- Outputs structured CSV or JSON files

---

## 🧠 Built For

This was created to:
- Build a directory of beauty salons in Paris
- Help agencies or clients analyze service providers by district
- Normalize unstructured listings using AI models

---

## 🛠 Technologies

- Python 3
- Playwright (browser automation)
- BeautifulSoup or `browser-use`
- Ollama (Mistral model) or OpenAI GPT-4 (optional)
- Pandas, CSV

---

## 🧪 Example Output

- Salon Name  
- Address  
- Postal Code / Arrondissement  
- Star Rating  
- Estimated Price Range (if available)

---

## 🔐 Access

🔒 Source code is private.  
This project demonstrates real-world data extraction and NLP-driven cleanup workflows.

---

## 🧑‍💻 Author

**TrkElnIt** – AI scraping and web automation expert  

