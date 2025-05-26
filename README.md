Project Overview
This project implements an automated customer support chatbot for an electronics retail company. The chatbot helps customers quickly get answers to common questions about smartphones, laptops, orders, company policies, and warranties — all without human intervention.

The chatbot supports multi-turn conversations by maintaining context across multiple messages, enabling natural follow-ups and improving user experience.

Features
Responds to FAQs on:

Latest smartphone and laptop specifications

Order tracking

Return policy

Payment methods

Warranty information

Maintains conversation context to handle follow-up questions

Lightweight, rule-based approach using keyword matching (no machine learning models needed)

Fully client-side implementation (HTML + JavaScript) — no backend or API key required

Easy to deploy and customize with your own FAQs and answers

How It Works
Knowledge Base:
A structured list of FAQs with associated keywords and answers.

Question Processing:
When a user submits a question, the chatbot searches the knowledge base for matching keywords.

Context Management:
The chatbot keeps track of recent conversation history to resolve ambiguous or follow-up questions.

Response Generation:
The chatbot returns the most relevant answer or asks for clarification if the question is unclear.
