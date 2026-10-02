# Customer Feedback Synthesizer

## Project Overview

Customer Feedback Synthesizer is an automated workflow built using n8n to collect and analyze customer reviews.

The workflow collects reviews, processes the feedback, analyzes the sentiment, and separates positive and negative reviews. Negative feedback can then be used to identify recurring complaints and feature requests.

## Goal

To automatically monitor customer feedback and identify recurring complaints and feature requests, helping the team prioritize bugs and improvements.

## Workflow

The workflow follows these steps:

1. Schedule Trigger
2. Fetch customer reviews using HTTP Request
3. Edit and prepare review data
4. Prepare reviews for analysis
5. Analyze the review using an AI model
6. Process the AI response using JavaScript
7. Retrieve data from Google Sheets
8. Check the sentiment
9. Separate positive and negative reviews
10. Append the processed reviews to Google Sheets

## Technologies Used

- n8n
- AI / LLM
- JavaScript
- Google Sheets
- HTTP Request
- App Store / Play Store review data

## Key Features

- Automated review collection
- AI-based sentiment analysis
- Positive and negative review classification
- Identification of customer complaints
- Structured storage in Google Sheets
- Automated workflow using n8n

## Expected Outcome

The system reduces manual review analysis and helps the team quickly understand customer feedback, recurring issues, and feature requests.

## Team Project

This project was developed as part of a team project to automate customer feedback analysis and improve the process of identifying customer issues.
