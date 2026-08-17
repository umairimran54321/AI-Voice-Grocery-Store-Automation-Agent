# AI-Voice-Grocery-Store-Automation-Agent
An end-to-end AI voice customer service and order automation system built with ElevenLabs, n8n, AI Agents, Webhooks, and Google Sheets.
🚀 Features
🛒 Place New Orders — Customers can order multiple grocery products using natural language.
✏️ Update Orders — Add products, change quantities, remove products, or update delivery addresses.
🔎 Order Inquiry — Retrieve order status, products, payment status, total price, and delivery information.
📞 Complaint Management — Handle customer complaints and generate unique complaint IDs.
📦 Inventory Validation — Check product availability and calculate remaining stock.
💰 Dynamic Order Pricing — Calculate product line totals and updated order grand totals.
🤖 AI-Powered Request Understanding — Converts natural-language voice requests into structured data.
🗣️ Voice Interaction — Customers communicate naturally through an ElevenLabs voice agent.
🔗 Webhook-Based Automation — Connects the voice agent to n8n workflows through APIs/webhooks.
📊 Google Sheets Integration — Used as the product inventory and order data source.
⚡ Automated Responses — Results from n8n workflows are returned to the voice agent for a natural customer response.
🏗️ Architecture
Customer
   ↓
ElevenLabs Voice Agent
   ↓
Natural Language Request
   ↓
n8n Webhook
   ↓
AI Agent
   ↓
Google Sheets
   ↓
Order / Inventory / Complaint Processing
   ↓
n8n Response
   ↓
ElevenLabs
   ↓
Natural Voice Response
🔧 Technologies
ElevenLabs Agents
n8n
AI Agents / LLMs
Google Sheets
REST APIs
Webhooks
JavaScript / n8n Code Nodes
JSON
Postman
🔄 Automated Workflows

The project contains four main workflows:

1. New Order

Customer Request → Product Search → Inventory Check → Price Calculation → Order Creation → Stock Update

2. Update Order

Order ID → Retrieve Order → Modify Product/Quantity/Address → Recalculate Total → Update Order

3. Order Inquiry

Order ID → Search Order → Retrieve Details → Generate Customer Response

4. Complaint

Customer Complaint → Extract Order ID → Generate Complaint ID → Record Complaint → Customer Response
🎯 Project Goal

The goal of this project is to demonstrate how voice AI can be combined with workflow automation and business systems to create an automated customer service solution that can understand requests, perform backend operations, and respond to customers without manual intervention.

This project demonstrates practical experience with AI automation, agentic workflows, API integration, voice AI, structured data processing, and business process automation.
