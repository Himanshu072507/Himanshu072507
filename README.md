# Hi, I'm Himanshu

Senior Product Manager who builds. I ship small, focused tools to scratch real itches — for myself, for the teams I work with, and for the field reps and operators downstream of the products I manage.

I prefer simple over clever, working over perfect, and learning by shipping over learning by reading.

## What I work on

Most of my side projects sit at the intersection of **product, AI, and user workflows** — dashboards that give PMs and users direct answers, lightweight agents that compress repetitive analysis, and prototypes I use to pressure-test ideas before pitching them to engineering.

## Projects

### [AI Ticket Analyzer](https://github.com/Himanshu072507/ai-ticket-analyzer-agent)
Upload a CSV/Excel of support tickets, get KPI cards, charts, and an AI-ranked priority list with recommendations. Streamlit + Plotly. Dual provider — Gemini (cloud) or Ollama (local, fully offline). Auto-detects columns, structured JSON output.

### [AQI Activity Advisor](https://github.com/Himanshu072507/aqi-activity-advisor)
Translates real-time AQI numbers into "should I go for a run right now?" answers. Two-agent pipeline: an analyst interprets pollutant data, an advisor returns a verdict, alternatives, and a best-time window. Streamlit + WAQI + Gemini/Groq.

### [Voice RAG Agent](https://github.com/Himanshu072507/voice-rag-agent)
Voice-in, voice-out RAG over uploaded documents. Hybrid retrieval (BM25 + dense embeddings, fused via RRF) with Cohere reranking; Cerebras Llama 3.1 for generation. Includes a hand-rolled eval harness with golden Q&A and per-question scoring.

### Sentry PM Dashboard
A PM-first refreshable view over Sentry errors — health status, punch list, release verdict, and a daily "your actions today" panel. Streamlit + Sentry REST API + optional Gemini for cluster narratives. 64 tests, rule-based fallbacks when no LLM key is set.

### Financial Tracker
Personal credit card spend tracker. Next.js (App Router) + Supabase + Recharts. Syncs Gmail transaction alerts, parses statement PDFs (Python/pypdf), and renders monthly trend + category donut charts.

### Resume Templates
Static HTML/CSS/JS resume builder — six templates across Professional and Creative styles, live preview editor, Firebase auth, Firestore save, PDF export. No build step, no framework.

### Diet Planner
Three-agent Streamlit prototype (Analyzer → Diet Planner → Workout Planner) that builds a personalized nutrition + workout plan from a user profile, with a mid-pipeline choice between three diet directions. Groq Llama 3.3 70B with an 8B fallback.

### IVR Survey Agent
Outbound IVR for survey collection — calls Indian mobile numbers, collects DTMF responses, runs two parallel Gemini agents (analyzer + summarizer) over the results. Next.js + Supabase + Twilio with a free mock telephony mode for dev.


## How I work

- **Less code, more clarity** — readable beats brief, simple beats clever.
- **Free tier first** — most of these run on free quotas (Gemini, Groq, Cerebras, Supabase, Vercel) so I can iterate without a billing meeting.
- **Ship to learn** — every project here started as a question I couldn't answer with a Google search.
