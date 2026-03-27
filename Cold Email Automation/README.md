# Cold Email Automation

A 2-part outbound automation system for personalized outreach and scheduled follow-up.

## 1) Initial Outreach
File: Cold email workflow Part 1. Initial Email.json

Description:
- Pulls leads from Google Sheets.
- Routes by partner type (College / Influencer / Brand / Other).
- Sends personalized first-touch email and logs tracking metadata.

Preview:
![Cold Email Part 1](../P1%20cold%20email.png)

## 2) Follow-up Scheduler
File: Cold email workflow Part 2. Follow-up Scheduler.json

Description:
- Runs daily and checks follow-up eligibility from tracking sheet.
- Sends stage-based follow-ups (follow-up 1, 2, final).
- Updates lifecycle status after each send.

Preview:
![Cold Email Part 2](../P2%20Codl%20email.png)
