# N8N Workflows
AI Automation Workflows – n8n Projects

This repository contains real-world AI automation systems built using n8n, LLMs, Google Sheets, Telegram, Gmail, and Webhooks.

The goal of these workflows is to automate business operations, lead generation, sales, support, and inventory monitoring using AI agents.

## 1. Smart Estate Telegram Bot

**📂 Workflow:** `Estate.json`

### 🔹 Overview
A Telegram-based real estate assistant that allows users to browse available properties dynamically.

### 🔹 Features
- Telegram Trigger integration
- Fetches property data from Google Sheets
- Filters only "Available" listings
- Dynamically generates inline keyboard buttons
- Displays property details (City, Bedrooms, Price)
- Interactive callback-based navigation

### 🔹 Tech Stack
- n8n
- Telegram Bot API
- Google Sheets
- JavaScript (dynamic formatting node)


## 2. AI Cold Email Outreach Agent

**📂 Workflow:** `Cold Email Outreach Agent.json`

### 🔹 Overview
An automated AI-powered cold email system that generates and sends personalized outreach emails daily.

### 🔹 Features
- Scheduled daily execution
- Reads prospects from Google Sheets
- AI-generated personalized email body (Gemini LLM)
- Structured formatting rules (max 120 words, professional tone)
- Sends emails via Gmail
- Updates Google Sheet with generated output

### 🔹 Tech Stack
- n8n
- Google Gemini (LLM)
- Gmail API
- Google Sheets


## 3. AI Inventory Management System

**📂 Workflow:** `Inventory Management System.json`

### 🔹 Overview
An intelligent stock monitoring system that detects low inventory and triggers approval-based restocking.

### 🔹 Features
- Scheduled stock check
- Compares Stock Qty vs Reorder Level
- AI-generated low-stock summary
- Sends approval email before restocking
- Conditional workflow branching
- Supplier information included in alerts

### 🔹 Tech Stack
- n8n
- Google Sheets
- Gmail
- Google Gemini LLM


## 4. Customer Support AI Chatbot (Order + Complaints)

**📂 Workflow:** `Customer Support Chatbot.json`

### 🔹 Overview
A Telegram-based AI customer support agent handling order tracking, cancellations, returns, exchanges, refunds, and complaints.

### 🔹 Features
- Order lookup via Google Sheets
- Policy-based approval system
- Automatic sheet updates
- Complaint registration with ID generation
- Complaint status tracking
- Human escalation logic
- Memory buffer for contextual conversation

### 🔹 Tech Stack
- n8n
- OpenAI (GPT-4.1-mini)
- Telegram API
- Google Sheets


## 5. AI Lead Capture & Sales Agent (Auto Body Shop)

**📂 Workflow:** `powell_updating.json`

**📂 Web Demo:** `Website_demo_chat_powell.json`

### 🔹 Overview
An AI receptionist for an auto body repair business that collects structured lead information and confirms appointments.

### 🔹 Features
- Webhook-based chat integration
- Structured slot-filling (Name, Car Model, Damage, Urgency, Contact)
- Regex validation for email & phone
- JSON-only AI responses
- Lead confirmation detection
- Automated email confirmation
- Conversation memory handling
- Clean JSON parsing & error handling

### 🔹 Tech Stack
- n8n
- Groq (LLaMA 3.1)
- Gmail API
- Webhooks
- JavaScript validation logic

## What This Repository Demonstrates

- AI Agent Design (LLM + memory + tools)
- Business Process Automation
- Lead Generation Systems
- CRM-style Data Management via Sheets
- Conditional Logic & Policy Enforcement
- Email Automation & Approval Flows
- Conversational AI with structured JSON outputs

## Why This Matters

Businesses adopting automation see:

- Up to 40–60% reduction in manual repetitive tasks
- Faster response times in customer support
- Scalable lead generation without increasing manpower

These workflows demonstrate how AI + automation can replace repetitive operational tasks while keeping human approval where necessary.
