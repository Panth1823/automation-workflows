# HeyGen Automation

AI media workflows that transform input content into generated videos.

## 1) Google Sheets to HeyGen Video
File: Google Sheets to HeyGen Video.json

Description:
- Watches/reads rows from Google Sheets.
- Sends script payload to HeyGen for video generation.
- Polls render status and writes resulting video URL back to sheet.

## 2) Telegram Voice to HeyGen Video
File: Telegram Voice to HeyGen Video.json

Description:
- Accepts voice input from Telegram.
- Transcribes speech and converts text to a HeyGen avatar video.
- Returns generated video back to user via Telegram.
