# TextLens — AI Text Analyzer
 
🔗 **Live demo: [ns-cehelsky.github.io/textlens](https://ns-cehelsky.github.io/textlens/)**
 
A web app for text analysis powered by the Groq API and LLaMA 3.3 70B. Works as a single HTML file — no server, no installation required.
 
## Features
 
- **5 analysis modes** — Summary, Keywords, Sentiment, Simple Explanation, Study Notes
- **File upload** — supports TXT, MD, PDF and DOCX (up to 3 files)
- **Drag & drop** — drag files directly into the app
- **Text statistics** — word count, sentence count and estimated reading time
## Usage
 
1. Open `TextLens.html` in your browser
2. Enter your [Groq API key](https://console.groq.com) and click **Save Key**
3. Upload files or paste text directly
4. Select an analysis mode from the left panel
5. Click **Analyze**
## Requirements
 
- A modern browser (Chrome, Firefox, Edge)
- Groq API key — free at [console.groq.com](https://console.groq.com)
## Technologies
 
- HTML / CSS / JavaScript
- [Groq API](https://groq.com) — LLaMA 3.3 70B
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF file reading
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) — DOCX file reading
