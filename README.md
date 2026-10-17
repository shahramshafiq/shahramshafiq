<div align="center">

# Shahram Shafiq

**Junior AI Engineer** | LLM applications, RAG, agents and voice AI

Computer Science student at FAST NUCES Islamabad. I build AI systems end to end: the models, the backends, the evaluation and the interface around them.

[![Portfolio](https://img.shields.io/badge/Portfolio-the--shahram--file-111827?style=flat-square&logo=vercel&logoColor=white)](https://the-shahram-file.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shahramshafiq-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shahramshafiq/)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shahramshafiqgoraya4363@gmail.com)

</div>

## About

I work as a Junior AI Engineer and study Computer Science at FAST NUCES. I like LLM systems that are measured, guarded and built to keep running, not just demos. Here is what I have learned by building them:

- **Real-time voice agents:** streaming speech-to-text, LLM and text-to-speech pipelines over WebSockets, with barge-in handling and low latency (Deepgram, OpenAI, ElevenLabs).
- **LLM backends:** async FastAPI services with tool calling, conversation memory, Valkey caching and rate limiting, server-sent events and background jobs.
- **Retrieval-augmented generation:** corrective RAG over long SEC filings with pgvector and LangGraph, cited answers, abstention when the evidence is missing, and accuracy tracked on a hand-built evaluation set.
- **MCP servers and guardrails:** tool servers for calendars and for inventory and orders, with NeMo Guardrails on input and output, tested against jailbreak and prompt-injection attempts.
- **Agents:** multi-agent pipelines in LangGraph, such as DevMind, which turns a GitHub issue into a tested pull request.
- **Also:** computer vision and automation (OpenCV, MediaPipe, OCR, Playwright), and fundamentals built from scratch in C++, Java, Python and x86 assembly.

Currently exploring system design for MCP and agent-to-agent (A2A) architectures.

## Projects

Listed in the order I built them, oldest first.

### AI engineering

| When | Project | What it does | Stack |
|---|---|---|---|
| Jun 2026 | [Community Health Worker Report Agent](https://github.com/shahramshafiq/chw-report-agent) | Structures field reports and flags urgency. [Live demo](https://chw-report-agent.streamlit.app) | Python, Streamlit, Groq |
| Jun 2026 | [DevMind](https://github.com/shahramshafiq/devmind) | Multi-agent pipeline that turns a GitHub issue into a tested pull request. [Live demo](https://devmind-theta.vercel.app) | Python, FastAPI, LangGraph, React, ChromaDB |
| Jun 2026 | [3D Reconstruction Portfolio](https://github.com/shahramshafiq/preservemy.world-internship) | Point cloud and mesh pipeline for heritage sites, with a Flask API and ML notebooks. [Site](https://shahramshafiq.github.io/preservemy.world-internship/) | Python, OpenCV, Flask |
| Jul 2026 | [AirCursor](https://github.com/shahramshafiq/aircursor) | Touch-free mouse control from hand gestures through any webcam | Python, MediaPipe, OpenCV |
| Aug 2026 | [Event Processing API](https://github.com/shahramshafiq/event-processing-fastapi) | Extracts PDF text in background jobs with live SSE progress and Valkey caching | Python, FastAPI, Valkey |
| Sep 2026 | [DevMate LLM API](https://github.com/shahramshafiq/devmate-llm-api) | LLM assistant backend with tool calling, Valkey memory and NeMo Guardrails checks | Python, FastAPI, OpenAI |
| Sep 2026 | [SEC Filings RAG](https://github.com/shahramshafiq/sec-filings-rag-qa) | Corrective RAG over SEC 10-K filings with cited answers and abstention | Python, FastAPI, LangGraph, pgvector |
| Sep 2026 | [Calendar MCP Assistant](https://github.com/shahramshafiq/google-calendar-mcp-assistant) | Chat assistant that manages tasks and Google Calendar through an MCP server | Python, FastAPI, MCP, OpenAI |
| Sep 2026 | [Order Management MCP](https://github.com/shahramshafiq/order-management-mcp-server) | MCP server for inventory and orders with a guardrailed OpenAI chat assistant | Python, MCP, NeMo Guardrails |
| Oct 2026 | [Streaming Voice Agent](https://github.com/shahramshafiq/streaming-voice-agent) | Low-latency voice agent with barge-in, built on streaming STT, LLM and TTS | Python, WebSockets, Deepgram, ElevenLabs |

### Computer science foundations

| When | Project | What it does | Stack |
|---|---|---|---|
| 2025 | [Galaxy Wars](https://github.com/shahramshafiq/galaxy-wars-game) | Arcade space shooter with three levels, power-ups and a boss | C++, SFML |
| 2026 | [Railway Management System](https://github.com/shahramshafiq/railway-management-system) | Command-line railway system with AVL trees, graphs and hash tables written from scratch | C++ |
| 2025 | [Super Mario in Assembly](https://github.com/shahramshafiq/super-mario-assembly) | Two-level platformer with enemies, power-ups and audio | x86 MASM, Irvine32 |
| 2026 | [INNsight Hotel Management](https://github.com/shahramshafiq/innsight-hotel-management) | JavaFX desktop app with a Botpress chatbot that books rooms | Java, JavaFX, SQLite |
| 2026 | [Pathfinder Visualizer](https://github.com/shahramshafiq/pathfinder-search-visualizer) | BFS, DFS, UCS and A* on an editable grid | Python, Tkinter |
| 2026 | [Course Scheduling GA](https://github.com/shahramshafiq/course-scheduling-genetic-algorithm) | Genetic algorithm that evolves weekly course schedules | Python, Tkinter |
| 2026 | [Course Timetabling CSP](https://github.com/shahramshafiq/course-timetabling-csp-solver) | Timetabling as a CSP with backtracking, MAC and min-conflicts | Python, Tkinter |
| 2026 | [CityMind](https://github.com/shahramshafiq/citymind-urban-intelligence) | City emergency simulator combining CSP, genetic algorithms, simulated annealing, A* and KNN | Python, Tkinter |

## Toolbox

| Area | Technologies |
|---|---|
| Languages | Python, JavaScript, Java, C++, SQL, x86 Assembly |
| AI and LLM | LangChain, LangGraph, RAG, MCP, NeMo Guardrails, tool calling, multi-agent systems |
| Voice and backend | FastAPI, Flask, WebSockets, SSE, Deepgram, ElevenLabs, Docker |
| Data | PostgreSQL, pgvector, ChromaDB, Valkey, SQLite |
| Vision and automation | OpenCV, MediaPipe, PyTorch, EasyOCR, Playwright |
| Tools | Git, GitHub, pytest, Postman, Streamlit |

<p align="center">
  <img height="150" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shahramshafiq&layout=compact&hide=html,css,jupyter%20notebook&theme=transparent&title_color=0969da&text_color=6e7681&hide_border=true" />
</p>
