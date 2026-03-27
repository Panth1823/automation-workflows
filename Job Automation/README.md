# Job Automation

Production-focused automation workflows for sourcing and maintaining high-quality job listings.

## 1) Job Scraper
File: 🚀 Job Scraper.json

Description:
- Scrapes jobs from multiple ATS/job-board sources daily.
- Normalizes records (title, company, location, work mode, salary, metadata).
- Writes deduplicated jobs to storage layers for downstream usage.

Preview:
![Job Scraper](../Job%20Scraper.png)

## 2) Job Deactivator
File: 🗑️ Job Deactivator.json

Description:
- Re-checks active job links on a schedule.
- Detects dead/redirected listings using response and redirect logic.
- Marks stale jobs inactive to keep the database and sheet clean.

Preview:
![Job Deactivator](../Job%20Deactivator.png)
