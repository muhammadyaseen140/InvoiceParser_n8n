📄 Manual invoice data entry is boring, so I built an AI agent to do it for me!

Typing invoice details into spreadsheets wastes time and invites mistakes. I automated the whole process with n8n and OpenAI.

How it works:

📂 Google Drive trigger: the moment a new invoice is uploaded, the workflow starts.

⬇️ Download and extract: the PDF is downloaded and its text is pulled out.

🧠 AI Information Extractor: OpenAI reads the messy invoice text and returns clean, structured fields.

📊 Google Sheets: every invoice is added as a new row, so the records stay organized automatically.

📧 Gmail notification: an AI-generated summary is sent by email, so I know it’s been processed.

What I learned:

- Turning unstructured documents (PDFs) into structured data with LLMs
- Defining extraction schemas so the AI returns consistent fields
- Chaining triggers, file handling, AI and apps into one pipeline

Drop in an invoice, and the data is ready in seconds. No typing, no copy-pasting. ⚡