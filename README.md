# Bulk Email Sender with Google Sheets & Apps Script

This project allows users to send personalized bulk emails using Gmail and a Google Sheet. The script uses Google Apps Script (JavaScript) to loop through a sheet with contact information and send customized emails.

## Features
- Send personalized emails using Gmail
- Read recipient data from Google Sheets
- Easy configuration and setup

## How to Use
1. Copy the script into your Google Sheets Script Editor.
2. Set up your sheet with headers like `Name`, `Email`, `Message`, etc.
3. Run the `sendEmails()` function.
4. Authorize the script to send emails from your account.

## Configuration
You can create a simple `config.json` to define the email template, subject, and delay between messages if needed.
