AuraDesk — Intelligent Customer Support Chatbot
AI-powered customer support agent for Indian businesses · Powered by Google Gemini


PRD = https://drive.google.com/file/d/1vrKlfTsh4_9YG7F0c4O8ZRHRuTPrSMcj/view?usp=drive_link

--------------------------------------------------------------------------------
Product Overview
The Problem:
Indian SMEs typically spend ₹15,000–50,000/month on human customer support agents to handle repetitive queries
Data shows that 60% of support tickets consist of the same 10-15 questions asked repeatedly, leading to high operational costs and slow response times

The Solution: AuraDesk

AuraDesk is an AI-driven support ecosystem that automates repetitive customer inquiries instantly. By leveraging the Google Gemini 2.0 Flash model, it reduces ticket volume, slashes operational costs, and improves response times from hours to mere seconds

Target Users: E-commerce stores, Food Delivery apps, EdTech platforms, and FinTech providers across India


--------------------------------------------------------------------------------
PM Case Study: The STAR Summary
Situation: Indian SMEs lose significant revenue and efficiency to manual handling of repetitive customer queries

Task: Build a multi-business AI support agent capable of adapting its personality, expertise, and language (Hindi/English) to diverse industries

Action: Developed AuraDesk using the Google Gemini LLM. Implemented four distinct business modes, conversation memory for context, and escalation logic for complex issues

Result: Projected 60% ticket deflection rate, potentially reducing support costs for SMEs from ₹50,000/month to under ₹5,000/month


--------------------------------------------------------------------------------
Key Features
4 Specialized Business Modes: E-Commerce, Food Delivery, EdTech, and FinTech—each with a unique persona and industry-specific expertise

Contextual Conversation Memory: Retains the last 6 messages to provide seamless, human-like contextual responses

Bilingual Capability: Native support for both Hindi and English to cater to the diverse Indian market

Smart Escalation Logic: Automatically identifies when a query is too complex and suggests a human agent handoff

Enterprise-Grade Resilience: Includes rate-limit handling to prevent crashes and a Privacy-First architecture where users bring their own API keys


--------------------------------------------------------------------------------
Success Metrics (PM Framework)
To measure the effectiveness of AuraDesk as a product, we track the following KPIs:
Metric
Target
Description
Ticket Deflection Rate>60%
Queries resolved by AI without human intervention

First Response Time<2 seconds
Ensuring near-instant user gratification

Resolution Rate>75%
Percentage of users whose queries are successfully solved

CSAT Score>4.2/5
User satisfaction rating post-interaction

Cost per Ticket<₹2
Massive reduction compared to ₹150 for human agents


--------------------------------------------------------------------------------
Tech Stack
Frontend: Streamlit (Custom Royal Dark Theme with Orbitron & Exo 2 fonts)

LLM Orchestration: LangChain

Brain: Google Gemini 2.0 Flash

Language: Python

Logic: Custom CSS and Python-based conversation management


--------------------------------------------------------------------------------
Product Roadmap
V1 (Current): 4 business modes, Gemini LLM integration, and conversation memory

V2 (Expansion): RAG (Retrieval-Augmented Generation) integration to train on specific company FAQ documents and WhatsApp API deployment

V3 (Scale): Advanced analytics dashboard for business owners, multi-agent routing, and voice support


--------------------------------------------------------------------------------
Installation & Local Setup
Clone the repository and follow the steps below to run AuraDesk on your local machine:
# Clone the repository
git clone https://github.com/Vivekbakade/AuraDesk

# Navigate to the project directory
cd AuraDesk

# Install dependencies
pip install -r requirements_auradesk.txt

# Set up your environment variables
echo "GOOGLE_API_KEY=your_key_here" > .env

# Run the application
streamlit run AuraDesk_app.py
Note: Obtain your free Gemini API key at aistudio.google.com.

--------------------------------------------------------------------------------
Business Model (Proposed)
Plan
Price
Features
Free
₹0
100 conversations/month
Startup
₹2,999/month
Unlimited chats + Custom FAQ training
Enterprise
₹9,999/month
Multi-agent + Analytics + WhatsApp Integration

--------------------------------------------------------------------------------
Developed by Vivek Bakade
Part of an AI Product Management Portfolio
Email Me | GitHub Profile
