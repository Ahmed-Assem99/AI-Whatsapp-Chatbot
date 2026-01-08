# 🤖 AI-Powered WhatsApp Chatbot for Any Business (n8n + RAG)

This project is a **production-ready WhatsApp AI chatbot** built entirely in **n8n**, designed to work for **any business or website**.

The chatbot automatically:
- Scrapes a business website
- Converts the content into a structured knowledge base (Encyclopedia)
- Uses **AI (LLM + RAG)** to answer customer questions
- Responds **in real-time via WhatsApp**

No manual training. No hardcoded FAQs.  
Just connect a website → chatbot is ready 🚀

---

## ✨ Key Features

- 🔗 **Website Auto-Scraping**
  - Crawls and scrapes all public pages of a business website
  - Filters media and irrelevant URLs
  - Aggregates content into one clean knowledge source

- 🧠 **RAG (Retrieval-Augmented Generation)**
  - Website content is transformed into a structured encyclopedia
  - AI answers are **strictly based on the scraped data**
  - No hallucinations, no made-up answers

- 💬 **WhatsApp Integration**
  - Customers ask questions directly on WhatsApp
  - AI replies instantly with accurate, business-specific answers

- 🧩 **Fully Built in n8n**
  - No backend code required
  - Visual, maintainable, and easy to customize
  - Client-friendly and scalable

- 🧠 **Conversation Memory**
  - Maintains chat context per user
  - More natural and human-like conversations

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **Firecrawl** – Website crawling & scraping
- **LangChain (n8n nodes)** – AI orchestration
- **LLM via OpenRouter (OpenAI-compatible models)**
- **WhatsApp Cloud API** – Messaging channel
- **RAG Architecture** – Website-based knowledge retrieval

---

## 🧠 How It Works (High-Level)

1. **Website URL Submission**
   - User submits a business website URL via form

2. **Website Crawling**
   - Firecrawl maps all internal pages
   - Media and irrelevant links are filtered out

3. **Content Scraping**
   - Each page is scraped and cleaned
   - Metadata + markdown content are extracted

4. **Knowledge Base Creation**
   - All pages are aggregated
   - AI restructures them into a clean encyclopedia

5. **AI Agent**
   - Uses the encyclopedia as its only knowledge source
   - Responds politely and accurately
   - Refuses to answer if information is not available

6. **WhatsApp Reply**
   - Final answer is sent back to the user on WhatsApp

---

## 📸 Use Cases

- 🏨 Hotels & Resorts  
- 🏥 Clinics & Medical Centers  
- 🏢 Corporate Websites  
- 🛒 E-commerce Stores  
- 🏫 Educational Institutions  
- 🏗️ Construction & Engineering Companies  
- 🏪 Any local or online business

---

## ⚙️ Requirements

Before importing the workflow, you’ll need:

- n8n (Cloud or Self-hosted)
- Firecrawl API key
- OpenRouter API key (or compatible LLM provider)
- WhatsApp Cloud API credentials
- A public business website to scrape

---

## 🚀 Setup Instructions

1. Clone this repository
2. Import the JSON workflow into **n8n**
3. Configure credentials:
   - Firecrawl
   - OpenRouter (LLM)
   - WhatsApp Cloud API
4. Activate the workflow
5. Submit a website URL
6. Start chatting on WhatsApp 🎉

---

## 🔒 AI Safety & Accuracy

- The AI **never invents information**
- Answers are strictly based on scraped website data
- If information is missing, the bot:
  - Clearly says it doesn’t know
  - Redirects users to human support

---

## 💼 Freelancing / Client Value

This solution is ideal for:
- SaaS chatbot services
- Monthly AI support retainers
- One-time chatbot setup for businesses
- White-label automation agencies

Clients get:
- 24/7 customer support
- Reduced human workload
- Zero training effort
- Fast deployment

---

## 📬 Contact

If you want this customized for your business or clients:
- GitHub: https://github.com/Ahmed-Assem99
- Email: ahmedassem13@gmail.com
