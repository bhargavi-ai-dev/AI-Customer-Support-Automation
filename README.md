# AI Customer Support Automation System

An end-to-end automated customer support pipeline built using **Make.com**, **Groq AI (LLM)**, **Google Sheets**, and **Gmail**.

## Project Workflow
1. **Trigger:** Monitors a Google Sheet for incoming customer feedback.
2. **Sentiment Analysis:** Uses an AI model to classify the customer message as `Positive` or `Negative`.
3. **Database Update:** Automatically logs the AI classification back into the Google Sheet.
4. **Smart Routing & Custom Reply:** Filters out `Negative` feedback, generates a personalized apology email using a second AI prompt, and sends it directly to the customer via Gmail.
