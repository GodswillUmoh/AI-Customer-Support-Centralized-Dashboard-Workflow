# AI-Customer-Support-Centralized-Dashboard-Workflow

## Overview

This project implements an AI-powered customer support automation system designed to streamline complaint handling, ticket management, and customer communication.

It combines AI classification, workflow automation, and centralized reporting to improve response speed, reduce manual workload, and enhance customer satisfaction.

---

## Solution Summary

The system automatically processes customer requests submitted via Google Forms, analyzes them using AI, and routes them to the appropriate channels for resolution.

---
## Workflows in n8n
<img width="1579" height="963" alt="Screenshot (747)" src="https://github.com/user-attachments/assets/e2947736-fa71-4617-a384-29e68c35ccc3" />

## Email Sample Automated Message
<img width="1796" height="639" alt="Screenshot (749)" src="https://github.com/user-attachments/assets/dc2874bd-2682-4d79-855d-4c85fd2b0375" />


## Email Sample2
<img width="1765" height="631" alt="Screenshot (748)" src="https://github.com/user-attachments/assets/806907c5-19fd-4015-b77d-35e7ed3f8ad1" />


## Workflow Architecture

```text
Google Forms
     ↓
n8n Trigger (Google Sheets)
     ↓
OpenAI Intent & Sentiment Analysis
     ↓
Request Classification
     ↓
Business Logic Routing
     ↓
Trello (Ticketing)
Gmail (Email Notifications)
Telegram (Alerts)
     ↓
Supabase (Data Storage)
     ↓
Google Sheets (Analytics Layer)
     ↓
Looker Studio (Dashboard)

## Trello Ticketing Visual
<img width="1510" height="1017" alt="Screenshot (745)" src="https://github.com/user-attachments/assets/646f3573-8cf2-4bf4-a08f-2c5567902d41" />




