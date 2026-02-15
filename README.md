🗞️ Autonomous AI News Agent
An intelligent, end-to-end automation pipeline that transforms the daily news cycle into a high-quality, illustrated digital briefing—fully automated with n8n.

🚀 Overview
This agent doesn't just find news; it curates it. It autonomously researches trending tech topics, synthesizes the information into executive summaries, generates custom context-aware AI artwork, and delivers the final report via a professional email newsletter.

🛠️ Tech Stack & Roles
- n8n 🧠 — The central "Brain" orchestrating the entire multi-step workflow.
- Tavily AI 🔍 — Advanced web-scraping and real-time news retrieval.
- Groq (Llama 3) ✍️ — High-speed LLM for concise, analytical news summarization.
- Hugging Face (FLUX) 🎨 — State-of-the-art image generation for custom article illustrations.
- ImgBB 🖼️ — Cloud hosting for dynamically generated AI assets.
- Google Sheets 📊 — Centralized database for long-term news archival and tracking.
- Gmail API 📩 — Automated distribution of formatted HTML news reports.

⚙️ How it Works
1. Trigger: A scheduled cron job starts the agent every morning at 8:00 AM. ⏰
2. Research: Tavily scans the web for breaking tech and AI news. 🌐
3. Summarize: Groq processes the findings into a clear, "too-long; didn't-read" summary. 📝
4. Visualize: Hugging Face uses the headline to paint a unique cover image for the story. 🎭
5. Store: The data (Headline, Summary, Image URL) is saved to Google Sheets. 📥
6. Deliver: A custom-styled HTML newsletter is sent to subscribers' Gmail inboxes. 📬

📈 Key Features
- 100% Autonomous: Zero manual intervention required from search to delivery.
- Dynamic Visuals: No generic stock photos; every image is unique and AI-generated.
