# 🧠 Insights Repository

> A centralised repo for product and marketing research insights — structured, searchable, and built to grow with every study.

This repository captures insights from user research, interviews, usability tests, and market feedback. It serves as a **shared knowledge base** for the Product and Marketing teams, helping us make informed, user-driven decisions.

---

## 📌 What This Repo Does

- Stores raw research materials (PDFs, transcripts)
- Generates structured insights using Claude
- Organizes insights by themes, user types, and relevance to Product or Marketing
- Supports collaboration and reuse of findings across teams

---

## 📁 Folder Structure
```
insights-repo/
├── .github/
│   └── workflows/
│       └── main.yml             # GitHub Actions workflow
├── pdfs/
│   └── README.md                # Placeholder for uploaded PDFs
├── insights/
│   └── README.md                # Placeholder for generated insights
├── scripts/
│   └── process_pdf.py           # Script to process PDFs and extract insights
├── config/
│   └── settings.json            # API keys and configuration settings
└── README.md                    # Main repo documentation
```
---

## 🧩 How It Works

1. Upload a PDF to the `/pdfs/` folder (either manually or via GitHub).
2. Run the `scripts/process_pdf.py` script OR paste the PDF into Claude with the prompt format.
3. Claude will return structured insights.
4. Save the output as a JSON or Markdown file inside `/insights/`.
5. Optionally, update the `index.json` or `insights.md` with a summary entry.

---

## 🧠 Insight Format (JSON Example)

```
json
{
  "id": "insight-042",
  "quote": "I had no idea the APR would change after I deposited.",
  "theme": "Yield expectations",
  "tags": ["APR", "onboarding", "DeFi"],
  "source": "interview-2025-07-01.pdf",
  "user_type": "Yield Maximizer"
}
```

## 🤝 How to Contribute

- Add new research PDFs to `/pdfs/`
- Run or manually use Claude to extract insights
- Save insights as structured `.json` or `.md` files in `/insights/`
- Follow consistent tagging and formatting for easier indexing

---

## 🧭 Maintainer

Made with ❤️ by **Sasha Luca**  
Contact: [sasha.tanase@gmail.com](mailto:sasha.tanase@gmail.com)

