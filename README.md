# AI Lead Generation & Social Discovery Automation

Automated lead generation workflow built in n8n that discovers local businesses 
from Google Maps and enriches them with emails, social profiles, AI summaries, 
and personalized outreach messages — all saved to Google Sheets.

## What it does

- Searches Google Maps using your custom queries
- Scrapes each business website for emails and contact info
- Finds missing social profiles (Instagram, Facebook, LinkedIn, Twitter, TikTok, YouTube)
- Validates emails and removes invalid ones
- Uses AI to generate a business summary and services list
- Writes a personalized outreach message for each lead
- Scores each lead from 0 to 10 based on digital presence
- Exports everything clean and organized to Google Sheets

## Requirements

- Serper API key
- Google Sheets OAuth
- Email validation API
- Ollama or any LLM endpoint

## How to use

- Import the JSON file into your n8n instance
- Connect your credentials
- Add your Google Sheet ID to the Sheets node
- Add search queries like "dentists in Pune" or "gyms in Delhi"
- Hit run and leads start filling your sheet automatically

## Template on n8n

Can find this template on the official n8n template library.
