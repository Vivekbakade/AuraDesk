ResolveAI — Intelligent Customer Support Chatbot

AI-powered customer support agent for Indian businesses · Powered by Google Gemini

Built by Vivek Bakade · vivekbakade14@gmail.com · LinkedIn · GitHub

 Product Overview
Problem: Indian SMEs spend ₹15,000–50,000/month on human customer support agents for repetitive queries. 60% of support tickets are the same 10 questions asked repeatedly.
Solution: ResolveAI is an AI-powered customer support chatbot that handles repetitive customer queries instantly — reducing ticket volume, cutting costs, and improving response time from hours to seconds.
Target Users: E-commerce stores, food delivery apps, EdTech platforms, FinTech apps — any Indian business with high support ticket volume.

 STAR Summary
SituationIndian SMEs waste millions on repetitive customer support queries that AI can handle instantlyTaskBuild a multi-business AI support agent that adapts its personality and expertise to different industriesActionBuilt ResolveAI using Google Gemini LLM with 4 business modes, conversation memory, Hindi+English support, and escalation handlingResultProjected 60% ticket deflection rate, reducing support cost from ₹50,000/month to under ₹5,000/month for SMEs

 Features

4 Business Modes — E-Commerce, Food Delivery, EdTech, FinTech — each with unique personality and expertise
Conversation Memory — remembers last 6 messages for contextual responses
Bilingual — Hindi + English support out of the box
Escalation Logic — knows when to escalate to a human agent
Rate Limit Handling — clean error messages instead of crashes
Privacy-First — user brings their own API key, zero data stored


 PM Metrics (How I'd Measure This Product)
MetricTargetTicket Deflection Rate>60%First Response Time<2 secondsResolution Rate>75%CSAT Score>4.2/5Escalation Rate<25%Cost per Ticket<₹2 (vs ₹150 human agent)

 Product Roadmap
V1 (Current) — 4 business modes, Gemini LLM, conversation memory
V2 — RAG integration (train on company's own FAQ docs), WhatsApp API
V3 — Analytics dashboard for businesses, multi-agent routing, voice support

🛠️ Tech Stack
Frontend:  Streamlit
LLM:       Google Gemini 2.0 Flash (via LangChain)
Language:  Python
Design:    Custom CSS — Orbitron + Exo 2 fonts, dark royal theme

 Run Locally
bashgit clone https://github.com/Vivekbakade/customer-support-chatbot
cd customer-support-chatbot
pip install -r requirements.txt
echo "GOOGLE_API_KEY=your_key_here" > .env
streamlit run app.py
Get your free Gemini API key at aistudio.google.com

 Business Model (If Productized)
PlanPriceFeaturesFree₹0100 conversations/monthStartup₹2,999/monthUnlimited + custom FAQ trainingEnterprise₹9,999/monthMulti-agent + analytics + WhatsApp

Part of Vivek Bakade's AI Product Management Portfolio
