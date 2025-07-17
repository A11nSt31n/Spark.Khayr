
# Khayr Aggregator

A community-centered data project to support @spark.khayr — an initiative aimed at empowering newly hijrah-ed Muslims in Singapore through information-sharing and volunteer opportunities. This project simulates real-world ETL work by automating the extraction and classification of Islamic events and volunteer drives. 

What started as a community support tool also laid the foundation for SUSS-relevant applications — from scraping unstructured event or calendar data to parsing feedback forms and automating information delivery.

---

## Real-World Applications for SUSS

The same data wrangling logic in this project could be applied to:

### 1. Academic Calendar Aggregator
- Extract: Scrape academic calendar pages
- Transform: Use OCR or HTML parsing to extract structured data
- Load: Export to CSV or SQL for reporting use
- Output: Dashboards for students or admin teams

### 2. Event Attendance Dashboard
- Extract: Ingest attendance logs from Excel/Forms
- Transform: Clean and normalize identifiers, flag late/no-shows
- Load: Into SQL or Azure tables
- Output: Power BI dashboards for engagement analysis

### 3. Survey Parser & Text Classifier
- Extract: Read free-text survey feedback
- Transform: Use NLP to identify themes and sentiment
- Load: Tag frequency and scores
- Output: Dashboards for department heads or course coordinators

### 4. Public Event Alert Bot
- Extract: Scrape SkillsFuture or SUSS public event pages
- Transform: Tag topics and sort by date/audience
- Load: Weekly digest file or Google Calendar sync
- Bonus: Auto-post to Telegram/IG

---

## Project Roadmap: Survey Parser & Text Classifier

This sub-project demonstrates how unstructured student feedback can be processed into structured insights for course improvement and engagement tracking.

### Phase 1: Set Up & Sample Data
- [x] Identify sample open-ended feedback dataset
- [ ] Upload sample CSV to repo
- [ ] Draft initial notebook structure

### Phase 2: Data Cleaning & Preprocessing
- [ ] Remove nulls, duplicates
- [ ] Normalize casing, punctuation
- [ ] Tokenize text using `spaCy`
- [ ] Remove stopwords

### Phase 3: Text Classification
- [ ] Create keyword tag list
- [ ] Classify responses by topic
- [ ] Optional: Add sentiment scoring

### Phase 4: Output & Visualization
- [ ] Generate tag frequency chart
- [ ] Sentiment trends per topic
- [ ] Export final dataset

### Phase 5: Reflection & Application
- [ ] Document assumptions and limitations
- [ ] Propose real-world application to SUSS departments

---

## Related Datasets
- [Graduate Employment Survey](https://data.gov.sg/dataset/graduate-employment-survey)
- [MOE Student Satisfaction Survey](https://data.gov.sg/dataset/school-satisfaction-survey)
- [SkillsFuture Events Feed](https://www.skillsfuture.gov.sg)

---

## Impact

Whether applied to community development or institutional feedback, this project reinforces how structured, human-centered data workflows can help organizations serve better, share faster, and improve more meaningfully.
