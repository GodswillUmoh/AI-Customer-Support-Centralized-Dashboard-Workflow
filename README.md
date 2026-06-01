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

## Email Sample2


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
