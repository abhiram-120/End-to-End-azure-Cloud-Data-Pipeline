Lacrimosa: A Framework for an AI-Native Organization

This repository contains the architectural blueprint for Lacrimosa, a conceptual framework for a company operated almost entirely by a hierarchy of specialized AI agents. This project was developed for the Google AI Hackathon (DevSprints) and was recognized as a Top 5% project out of over 400 submissions for its vision and comprehensive system design.
The core idea is to move beyond single-task AI tools and design an entire, scalable organization where roles, responsibilities, and workflows are executed by interconnected AI agents.
 The Architecture
The Lacrimosa framework is a hierarchical system designed to mirror and automate a traditional corporate structure. The main artifact of this project is the visual architecture, which you can see below.
You can view the interactive, high-resolution version on FigJam:

The architecture is broken down into four key layers:
Human Executive Team: A small group of human strategists who provide top-level direction, set objectives, and oversee the Chief AI Agent.
Chief AI Agent: The central "CEO" agent responsible for interpreting human commands, delegating tasks to departments, and ensuring organizational alignment.
Departmental AI: Specialized "Head of Department" agents (e.g., Head of Sales, Head of Marketing) that manage their own teams of functional agents. Each department has its own "AI Brain" or knowledge base.
Individual Agents: The workhorses of the organization. These are highly specialized agents designed to perform specific tasks, such as:
Automated CRM Enrichment: Fetching and updating lead data.
Auto Email Labelling & Draft Creator: Organizing inboxes and preparing replies.
Content Scheduler Agent: Planning and publishing social media content.
Ad Performance Evaluator Agent: Analyzing marketing campaign data.
 Tech Stack & Tools
This framework is tool-agnostic, but the prototype was designed with a specific set of modern AI and automation platforms in mind. The agents would leverage these tools to perform their tasks.
Orchestration & Automation: n8n
Large Language Models (LLMs): Google AI APIs (Gemini/PaLM), Claude 3, OpenAI GPT-4
Communication: Slack, Discord, Email (Gmail API)
Knowledge Base: Google Drive, Notion, Vector Databases
Productivity & CRM: Google Sheets, HubSpot API, Trello API
External Data APIs: Various APIs for market data, news, etc.
 Project Roadmap
The project was presented with a phased implementation roadmap to demonstrate how such an organization could be built incrementally.
Phase 1: Core Revenue Agents (First 8 Agents)
Focus on automating the sales and marketing funnels to establish a self-funding operational loop.
Includes agents for CRM enrichment, email outreach, and content ideation.
Phase 2: Back-Office & Operations
Develop agents for HR, Finance, and Management (e.g., Payroll Agent, Bookkeeping Agent, Calendar Manager).
Goal: Automate all internal administrative overhead.
Phase 3: Product & Expansion
Build agents for product development, R&D, and strategic analysis.
Includes agents like Ad Trend Analyser and Leads Prioritization Agent.
STATUS
This project is a conceptual blueprint and system design while some parts of the system are implemented. The repository serves to document the architecture, agent roles, and strategic thinking behind the Lacrimosa framework. It is not a functional, deployed software application. Its purpose is to showcase high-level system design and AI workflow architecture skills.
