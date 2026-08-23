# 500ai
What is this?
A curated collection of 500+ AI agent projects — production examples, tutorials, and working code spanning every major framework (LangGraph, CrewAI, AutoGen, Agno) and industry (Healthcare, Finance, Education, Cybersecurity, and more).

Who it's for:

🧑‍💻 Developers building their first or next AI agent
🔬 Researchers surveying the agent landscape
🏢 Teams evaluating frameworks for production use
🎓 Students learning agent architectures from real examples
⚡ Quick Start
Pick a framework and run an agent in under 5 minutes:

# Clone the repo
git clone https://github.com/ashishpatel26/500-AI-Agents-Projects.git
cd 500-AI-Agents-Projects

# Run any agent from the agents/ directory
cd agents/01-web-research-agent
pip install -r requirements.txt
cp .env.example .env        # add your API key
python agent.py
All agents in agents/ are self-contained with their own requirements.txt and .env.example. No monorepo setup needed.

🗺️ Navigation Guide
I want to...	Go to
Run a working agent right now	agents/
Browse by AI framework	Framework-wise Use Cases
Browse by industry	Industry Use Cases
Understand which framework to use	Framework Comparison
Add my own agent	Contributing
Learn with a course	crewai_mcp_course/
📊 Framework Comparison
Choosing a framework? Here's when to use each:

Framework	Best For	Complexity	Multi-Agent	Streaming	Local LLM
LangGraph	Stateful workflows, RAG pipelines, complex graphs	⭐⭐⭐	✅	✅	✅
CrewAI	Role-based teams, business automation, rapid prototyping	⭐⭐	✅	✅	✅
AutoGen	Code generation, research, self-healing workflows	⭐⭐⭐	✅	✅	✅
Agno	Lightweight single agents, tool integration, fast iteration	⭐	✅	✅	✅
LlamaIndex	Document Q&A, enterprise RAG, data pipelines	⭐⭐	⚠️	✅	✅
Quick decision guide:

Just starting out → Agno or CrewAI
Need stateful graphs + RAG → LangGraph
Building code-writing / research agents → AutoGen
Enterprise document pipelines → LlamaIndex
🏭 Industry Use Cases
Industry Mind Map

Use Case	Industry	Description	Code
HIA (Health Insights Agent)	Healthcare	Analyses medical reports and provides health insights	GitHub
AI Health Assistant	Healthcare	Diagnoses and monitors diseases using patient data	GitHub
Automated Trading Bot	Finance	Automates stock trading with real-time market analysis	GitHub
Agent Wallet SDK	Finance	Non-custodial smart contract wallet SDK for AI agents with enforced spend limits	GitHub
Virtual AI Tutor	Education	Provides personalized education tailored to users	GitHub
24/7 AI Chatbot	Customer Service	Handles customer queries around the clock	GitHub
Product Recommendation Agent	Retail	Suggests products based on user preferences and history	GitHub
Self-Driving Delivery Agent	Transportation	Optimizes routes and autonomously delivers packages	GitHub
Factory Process Monitoring Agent	Manufacturing	Monitors production lines and ensures quality control	GitHub
Property Pricing Agent	Real Estate	Analyzes market trends to determine property prices	GitHub
Smart Farming Assistant	Agriculture	Provides insights on crop health and yield predictions	GitHub
Energy Demand Forecasting Agent	Energy	Predicts energy usage to optimize grid management	GitHub
Content Personalization Agent	Entertainment	Recommends personalized media based on preferences	GitHub
Legal Document Review Assistant	Legal	Automates document review and highlights key clauses	GitHub
Recruitment Recommendation Agent	Human Resources	Suggests best-fit candidates for job openings	GitHub
Virtual Travel Assistant	Hospitality	Plans travel itineraries based on preferences	GitHub
AI Game Companion Agent	Gaming	Enhances player experience with real-time assistance	GitHub
Real-Time Threat Detection Agent	Cybersecurity	Identifies potential threats and mitigates attacks	GitHub
E-commerce Personal Shopper Agent	E-commerce	Helps customers find products they'll love	GitHub
Logistics Optimization Agent	Supply Chain	Plans efficient delivery routes and manages inventory	GitHub
Vibe Hacking Agent	Cybersecurity	Autonomous Multi-Agent Based Red Team Testing Service	GitHub
Agent Memory Guard	Cybersecurity	Detects and blocks memory poisoning attacks (OWASP ASI06) in AI agent memory stores	GitHub
Citadel	Software Development	Orchestrates Claude Code agent fleets with lifecycle hooks, skills, campaign management, and postmortem-driven architecture	GitHub
MediSuite-AI-Agent	Health Insurance	Automates hospital / insurance claiming workflow	GitHub
Lina Egyptian Medical Chatbot	Healthcare	Egyptian medical assistant chatbot	GitHub
NextRole (AI Career Assistant)	Human Resources	Tailors a resume to a job description and generates interview prep plus a day-of battlecard via a multi-agent system	GitHub
PII Sanitization Agent	Privacy/Compliance	Redacts PII (emails, phones, national IDs, bank accounts, API keys) from text before it reaches an LLM; fail-closed, multilingual, on-chain proof via TrustBoost	GitHub
🔧 Browse by Framework
CrewAI
Role-based multi-agent framework. Great for business automation.

Use Case	Industry	Description	GitHub
📧 Email Auto Responder Flow	Communication	Automates email responses based on predefined criteria	GitHub
📝 Meeting Assistant Flow	Productivity	Organizes meetings, scheduling and agenda preparation	GitHub
🔄 Self Evaluation Loop Flow	Human Resources	Facilitates self-assessment for performance reviews	GitHub
📈 Lead Score Flow	Sales	Evaluates and scores potential leads to prioritize outreach	GitHub
📊 Marketing Strategy Generator	Marketing	Develops marketing strategies by analyzing market trends	GitHub
📝 Job Posting Generator	Recruitment	Creates job postings by analyzing job requirements	GitHub
🔄 Recruitment Workflow	Recruitment	Streamlines recruitment by automating hiring tasks	GitHub
🔍 Match Profile to Positions	Recruitment	Matches candidate profiles to suitable job positions	GitHub
📸 Instagram Post Generator	Social Media	Generates and schedules Instagram posts automatically	GitHub
🌐 Landing Page Generator	Web Development	Automates creation of landing pages for websites	GitHub
🎮 Game Builder Crew	Game Development	Assists in game development by automating aspects of creation	GitHub
💹 Stock Analysis Tool	Finance	Provides tools for analyzing stock market data	GitHub
🗺️ Trip Planner	Travel	Assists in planning trips with itineraries	GitHub
🎁 Surprise Trip Planner	Travel	Plans surprise trips based on user preferences	GitHub
📚 Write a Book with Flows	Creative Writing	Assists authors with structured writing workflows	GitHub
🎬 Screenplay Writer	Creative Writing	Aids in writing screenplays with templates and guidance	GitHub
✅ Markdown Validator	Documentation	Validates Markdown files for proper formatting	GitHub
🧠 Meta Quest Knowledge	Knowledge Management	Manages Meta Quest knowledge for information retrieval	GitHub
🤖 NVIDIA Models Integration	AI Integration	Integrates NVIDIA AI models into workflows	GitHub
🗂️ Prep for a Meeting	Productivity	Prepares meeting materials and sets agendas	GitHub
🛠️ Starter Template	Development	Starter template for new CrewAI projects	GitHub
🔗 CrewAI + LangGraph Integration	AI Integration	Integration between CrewAI and LangGraph	GitHub
AutoGen
Microsoft's framework for code generation, execution, and multi-agent research.

Code Generation, Execution, and Debugging

Use Case	Industry	Description	Notebook
🤖 Automated Task Solving with Code Gen, Execution & Debugging	Software Development	Demonstrates automated task-solving by generating, executing, and debugging code	Notebook
🧑‍💻 Code Generation and Q&A with Retrieval Augmented Agents	Software Development	Generates code and answers questions using retrieval-augmented methods	Notebook
🧠 Code Generation and Q&A with Qdrant-based Retrieval	Software Development	Utilizes Qdrant for enhanced retrieval-augmented agent performance	Notebook
Multi-Agent Collaboration

Use Case	Industry	Description	Notebook
🤝 Group Chat (3 members, 1 manager)	Collaboration	Demonstrates group task-solving via multi-agent collaboration	Notebook
📊 Data Visualization by Group Chat	Data Analysis	Uses multi-agent collaboration to create data visualizations	Notebook
🧩 Complex Task Solving by Group Chat (6 members)	Collaboration	Solves complex tasks collaboratively with a larger group	Notebook
🧑‍💻 Task Solving with Coding & Planning Agents	Planning & Dev	Combines coding and planning agents for solving tasks	Notebook
📐 Task Solving with Graph Transition Paths	Collaboration	Uses predefined transition paths in a graph for solving tasks	Notebook
🧠 SocietyOfMindAgent Inner-Monologue	Cognitive Sciences	Simulates inner-monologue for problem-solving using group chats	Notebook
🔧 Group Chat with Custom Speaker Selection	Collaboration	Implements a custom function for speaker selection	Notebook
Sequential Multi-Agent Chats

Use Case	Industry	Description	Notebook
🔄 Sequential Task-Solving (single initiating agent)	Workflow Automation	Automates sequential task-solving with a single initiating agent	Notebook
⏳ Async Sequential Task-Solving	Workflow Automation	Handles asynchronous task-solving in a sequence of chats	Notebook
🤝 Sequential Chats with Different Initiating Agents	Workflow Automation	Sequential task-solving with different agents initiating each chat	Notebook
Nested Chats

Use Case	Industry	Description	Notebook
🧠 Solving Complex Tasks with Nested Chats	Problem Solving	Uses nested chats to solve hierarchical and complex problems	Notebook
🔄 Sequence of Nested Chats	Problem Solving	Demonstrates sequential task-solving using nested chats	Notebook
🏭 OptiGuide Supply Chain with Nested Chats	Supply Chain	Solves supply chain optimization using nested chats	Notebook
♟️ Conversational Chess with Nested Chats	Gaming	Uses nested chats for playing conversational chess with tools	Notebook
Tools

Use Case	Industry	Description	Notebook
🌐 Web Search: Solve Tasks Requiring Web Info	Information Retrieval	Searches the web to gather information for completing tasks	Notebook
🔧 Use Provided Tools as Functions	Tool Integration	Demonstrates how to use pre-provided tools as callable functions	Notebook
📚 RAG Group Chat	Collaboration	Enables group chat with Retrieval Augmented Generation	Notebook
🔊 Agent Chat with Whisper	Audio Processing	AI agent for transcription and translation using Whisper	Notebook
📊 SQL: Natural Language to SQL Query	Database Management	Converts natural language inputs into SQL queries	Notebook
Multimodal Agents

Use Case	Industry	Description	Notebook
🎨 Multimodal Agent with DALLE and GPT-4V	Multimedia AI	Combines DALLE and GPT-4V for multimodal agent communication	Notebook
🖌️ Multimodal Agent with Llava	Image Processing	Uses Llava for multimodal agent conversations	Notebook
🖼️ Multimodal Agent with GPT-4V	Multimedia AI	Leverages GPT-4V for visual and conversational interactions	Notebook
Observability & Evaluation

Use Case	Industry	Description	Notebook
📊 AgentEval: Multi-Agent Assessment System	Performance Evaluation	Evaluating LLM-based application utility	Notebook
📊 Track LLM Calls and Errors using AgentOps	Monitoring & Analytics	Monitors LLM interactions, tool usage, and errors	Notebook
🏗️ Auto Build Multi-agent System with AgentBuilder	AI Development	Automatically builds multi-agent systems	Notebook
Agno
Lightweight, fast agent framework. Best for single-agent tools and rapid prototyping.

Use Case	Industry	Description	Code
🤖 Support Agent	AI Framework Support	Real-time answers, explanations, and code examples for Agno framework	Python
🎥 YouTube Agent	Media & Content	Analyzes YouTube videos: summaries, timestamps, themes	Python
📊 Finance Agent (Thinking)	Finance	Real-time stock insights, analyst recommendations, financial deep-dives	Python
📚 Study Partner	Education	Finds resources, answers questions, creates study plans	Python
🛍️ Shopping Partner Agent	E-commerce	Product recommender based on preferences from Amazon, Flipkart	Python
🎓 Research Scholar Agent	Education / Research	Advanced academic searches, publication analysis, structured reports	Python
🧠 Research Agent	Media & Journalism	Deep investigations, NYT-style reports	Python
🍳 Recipe Creator	Food & Culinary	Personalized recipes based on ingredients and preferences	Python
🧠 Financial Reasoning Agent	Finance	Claude 3.5 Sonnet-based stock analysis with Yahoo Finance data	Python
🤖 Readme Generator Agent	Software Dev	Generates high-quality READMEs for GitHub repos	Python
🎬 Movie Recommendation Agent	Entertainment	Personalized movie recommendations using Exa and GPT-4o	Python
🔍 Media Trend Analysis Agent	Media & News	Analyzes emerging trends and influencers from digital platforms	Python
⚖️ Legal Document Analysis Agent	Legal Tech	Analyzes legal PDFs and provides insights using vector embeddings	Python
🤔 DeepKnowledge	Research	Iterative search through knowledge base with deep reasoning	Python
📚 Book Recommendation Agent	Publishing & Media	Personalized book suggestions using literary data and reader preferences	Python
🏠 MCP Airbnb Agent	Hospitality	Search Airbnb listings with MCP and Llama 4	Python
🤖 Agno Assist Agent	AI Framework	GPT-4o agent for Agno framework Q&A with hybrid search	Python
LangGraph
State-machine framework for complex, stateful agent workflows and RAG pipelines.

Use Case	Industry	Description	Code
🤖 Chatbot Simulation Evaluation	AI / QA	Simulate user interactions to evaluate chatbot performance	Python
🧠 Information Gathering via Prompting	Research	LangGraph workflow using prompting to gather information	Python
🧠 Code Assistant with LangGraph	Software Development	Resilient code assistant with error checking and iterative refinement	Python
🧑‍💼 Customer Support Agent	Customer Support	Graph-based agent for handling customer inquiries	Python
🔁 Extraction with Retries	Data Extraction	Retry mechanisms for robust data extraction	Python
🧠 Multi-Agent Workflow (Supervisor)	Workflow Orchestration	Supervisor agent orchestrating multiple specialized agents	Python
🧠 Hierarchical Agent Teams	Workflow Orchestration	Top-level supervisor delegates to specialized sub-agents	Python
🤝 Multi-Agent Collaboration	Workflow Orchestration	Multiple specialized agents working together on complex tasks	Python
🧠 Plan-and-Execute Agent	Workflow Orchestration	Agent generates multi-step plan then executes sequentially	Python
🧠 SQL Agent	Database Interaction	Agent answers questions about SQL databases	Python
🧠 Reflection Agent	Workflow Orchestration	Agent critiques and revises its own outputs	Python
🧠 Reflexion Agent	Workflow Orchestration	Agent reflects on actions for iterative improvement	Python
🧠 Adaptive RAG	Information Retrieval	Dynamic retrieval adjusting based on query complexity	Python
🤖 Agentic RAG	Intelligent Agents	Agent determines best retrieval strategy before generating response	Python
🧠 Corrective RAG (CRAG)	Information Retrieval	Evaluates and refines retrieved documents before generation	Python
🧠 Self-RAG	Information Retrieval	System reflects on responses and retrieves additional info if needed	Python
🧠 Adaptive RAG (Local)	Information Retrieval	Adaptive RAG with local models for offline use	Python
🧠 Self-RAG (Local)	Information Retrieval	Self-RAG using local models and data sources	Python
🤝 Contributing
Contributions are welcome! 🎉 This repo grows through community contributions.

Ways to contribute:

Add a working agent — create a folder in agents/ with runnable code
Add an external link — add a row to the industry or framework tables
Fix a broken link — open an issue or PR
Improve documentation — fix typos, add context, improve examples
To contribute:

Fork the repository
Create a branch: feat/agent-name or fix/description
Add your changes following the Contributing Guidelines
Open a PR using the PR template
See CONTRIBUTION.md for full requirements (metadata.yaml, requirements.txt, etc.).

Star History
Star History Chart

Regenerated weekly from the GitHub API by .github/workflows/star-history.yml. Click the chart for the interactive version.

📜 License
This repository is licensed under the MIT License. See the LICENSE file for more information.

