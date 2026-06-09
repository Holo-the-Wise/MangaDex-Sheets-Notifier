# MangaDex-Sheets-Notifier

Tracks MangaDex series through the MangaDex API, stores tracked manga metadata in Google Sheets, and sends update notifications to Discord channels via webhooks.

## Requirements

- Google Account
- Google Sheets
- Google Apps Script
- Discord webhook URL
- Internet access to the MangaDex API

## Setup

### 1. Create a Google Sheet

Create a new Google Sheet containing the following worksheets:

#### MangaList

Stores the list of manga to monitor.

#### Logs

Stores execution logs and errors.

### 2. Create the Apps Script Project

1. Open the Google Sheet.
2. Select **Extensions → Apps Script**.
3. Copy the project files into the Apps Script editor.
4. Save the project.

## Configuration

### Script Configuration
