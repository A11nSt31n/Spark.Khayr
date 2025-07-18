# Khayr Aggregator
Aggregator is defined to be a website or program that collects related items of content and displays them or links to them. This is a community-focused project to support @spark.khayr in its efforts.

## Project Goal
To automate the collection, categorization, and organization of Islamic events, workshops, classes, and volunteer drives across Singapore, enabling easier dissemination through Instagram and public calendars. This aims to reduce manual workload and improve accessibility for seekers of knowledge.

## Objectives

- Extract event details from public Telegram channels (e.g. Raudhatul Jannah SG)
- Parse poster images and event blurbs using OCR and NLP
- Automatically populate a structured dataset with:
  - Date & Time
  - Venue / Online platform
  - Target audience (e.g. ladies-only, youth, open)
  - Price (free/paid)
  - Duration / commitment period
  - Recurring class indicator
  - Event type (e.g. talk, class, volunteer drive)
- Build a simple dashboard or feed to review, filter, and schedule posts/stories

## ⚙️ Tools & Tech Stack

### Core:
- Python (main scripting logic)
  - pytesseract for OCR (poster reading)
  - pandas for data wrangling
  - re, spaCy or nltk for text extraction
- Telegram API or telethon for scraping channel posts
- Instagram Graph API (if feasible) or manual scheduling via creator studio

### Optional Cloud:
- Microsoft Fabric or Azure Data Factory: For orchestrating daily scraping + transformation (if scaling up)
- Power BI or Streamlit/Dash: For internal dashboard to filter events & export calendar links
- Google Calendar API: For automated public calendar publishing

## Folder Structure

```
khayr-aggregator/
│
├── data/                   # Raw + cleaned event data
├── scripts/                # Python scripts for scraping, OCR, NLP
├── notebooks/              # Prototypes and exploratory analysis
├── outputs/                # Exported CSVs, calendar links, etc.
└── README.md               # You are here
```

## Future Ideas

- Weekly digest newsletter generation
- Community submission form (via Airtable or Formsg)
- Community pulse board for specific workshop requests with polls, for vendors and Asatizah's consideration

## Impact

By streamlining how Islamic events and initiatives are shared, this tool aims to:
- Support spiritual seekers in navigating their hijrah and ilm-seeking journey with ease
- Help organizations and mosques reach wider audiences
- Promote volunteerism within the ummah

## Contact

Built by @aiin_stein | Project under @spark.khayr
