# Personalized AI Student Newsletter Automation

## About
This project uses n8n to automatically collect AI and cybersecurity news and generate personalized learning newsletters for students.
An n8n automation that creates personalized AI and cybersecurity newsletters for students using RSS, Google Sheets, Gemini, and Gmail.

## Features
- Collects news from RSS feeds.
- Uses Google Gemini to summarize and personalize news.
- Collects student preferences through Google Forms.
- Stores student preferences in Google Sheets.
- Generates newsletters based on interests, skill level, and content preferences.
- Sends personalized emails through Gmail.

## Technologies
- n8n
- Google Forms
- Google Sheets
- Google Gemini
- RSS
- Gmail

## Workflow
1. Collect news articles from RSS feeds.
2. Process and summarize the articles using an AI model.
3. Read student preferences from Google Sheets.
4. Generate a personalized newsletter for each eligible student.
5. Convert the newsletter into HTML.
6. Send it to the student's email address.

## Setup
Users should create their own Google Form, Google Sheets, Gemini credentials, and Gmail credentials, then configure the n8n workflow with their own accounts.

## Privacy
This repository does not contain real student registration responses or private credentials. Use sample data when testing.

## Project Status
Initial working version. Improvements to personalization and workflow reliability are ongoing.
