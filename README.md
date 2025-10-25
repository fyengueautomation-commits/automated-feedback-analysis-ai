# automated-feedback-analysis-ai
This project demonstrates how to automate customer feedback analysis using AI and no-code tools. Acting as a Customer Success Manager at a small online business, I built a system that collects feedback, analyzes sentiment, summarizes responses, and alerts the team to urgent issues — all in real time.

📊 Automated Feedback Analysis Workflow
AI-Powered Sentiment Detection & Insights | Built by Francois O Yengue

🧩 Project Overview
This project demonstrates how to automate customer feedback analysis using AI and no-code tools. Acting as a Customer Success Manager at a small online business, I built a system that collects feedback, analyzes sentiment, summarizes responses, and alerts the team to urgent issues — all in real time.

🎯 Objective
Create an automated workflow that:

Collects customer feedback via Google Forms

Sends responses to Gemini AI for sentiment analysis and summarization

Parses AI output using Make

Stores structured results in Google Sheets

Sends email alerts for negative feedback (optional but implemented)

🛠️ Tools Used
Tool	Purpose
Google Forms	Collect customer feedback
Make (Integromat)	Automate workflow steps
Gemini AI	Analyze sentiment and summarize messages
Google Sheets	Store structured feedback data
Gmail	Send alerts for negative sentiment
🧠 AI Prompt Format
Used with Gemini 1.5 Flash module:

json
{
  "sentiment": "[Positive/Neutral/Negative]",
  "summary": "[Your summary here]"
}
This format ensures consistent parsing and structured output for downstream automation.

🔄 Workflow Steps
Google Form Setup

Question 1: Satisfaction rating (multiple choice)

Question 2: Open-ended feedback

Submitted 7 varied test responses

Trigger in Make

Watches for new form submissions

Send to Gemini AI

Uses structured prompt to classify sentiment and summarize

Parse JSON Output

Extracts sentiment and summary fields

Store in Google Sheets

Adds timestamp, sentiment, and summary

Email Alerts

If sentiment = “Negative”, sends alert with summary and sheet link

Presentation

Created a Google Slides deck to document the workflow and findings

Includes screenshots, data insights, and optional enhancements

📈 Results & Insights
Sentiment Accuracy: 87.5% correctly classified

Negative Feedback Rate: 37.5%

Alerts Triggered: 3 email notifications

Response Speed: 7 entries collected in under 3 minutes

Business Impact: One refund request flagged immediately

🚀 Optional Enhancements
Slack or WhatsApp alerts

Trello card creation for task tracking

Escalation logic for high-value complaints

Weekly sentiment digest reports

CRM integration for customer health scoring

📎 Project Assets
📄 Workflow Blueprint (Make)

📊 Google Sheet with Feedback Data

📋 Google Form

📽️ Presentation Deck

👤 Author
Francois O Yengue AI Automation | Business Process Optimization 📧 fyengue.automation@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/feed/)  
🔗 [GitHub](https://github.com/fyengueautomation-commits)
