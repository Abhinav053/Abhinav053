<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6E40C9&height=120&section=header&text=&animation=fadeIn"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1000&color=6E40C9&center=true&vCenter=true&width=800&lines=Abhinav+Ranjan+Singh;Backend+Developer+%7C+AI+Engineer;Full+Stack+Developer)](https://git.io/typing-svg)

<br/>

![B.Tech ECE](https://img.shields.io/badge/B.Tech-Electronics_%26_Communication-6E40C9?style=for-the-badge&logo=academia&logoColor=white)
![IoT Specialization](https://img.shields.io/badge/Specialization-IoT-7C3AED?style=for-the-badge&logo=raspberrypi&logoColor=white)
![IIIT Nagpur](https://img.shields.io/badge/IIIT-Nagpur_%7C_2023--2027-4F46E5?style=for-the-badge&logo=google-scholar&logoColor=white)
![India](https://img.shields.io/badge/Location-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-6E40C9?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Abhinav053)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abhinav-singh)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhinav@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abhinav053)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Abhinav053&label=Profile+Views&color=6E40C9&style=flat-square)
![GitHub Followers](https://img.shields.io/github/followers/Abhinav053?label=Followers&color=6E40C9&style=flat-square&logo=github)
![GitHub Stars](https://img.shields.io/github/stars/Abhinav053?label=Total+Stars&color=6E40C9&style=flat-square&logo=github)

</div>

---

## About

I am a backend-focused software engineer and AI practitioner currently pursuing a B.Tech in Electronics & Communication Engineering with an IoT specialization at IIIT Nagpur. My engineering philosophy centers on building systems that are reliable at scale, observable in production, and architected to evolve — not just code that works once.

My backend work spans distributed microservices with async messaging via RabbitMQ, real-time infrastructure with Socket.IO and Redis GEO, and API gateway patterns for service routing and rate limiting. On the AI side, I design and ship end-to-end LLM pipelines using LangChain, RAG with ChromaDB, and Whisper-powered transcription — systems that are grounded, low-latency, and production-aware rather than demo-grade.

I approach every project with a product engineering mindset: performance and correctness are not afterthoughts, they are the constraints around which good design is built. I care about system observability, failure modes, and the engineering decisions that separate prototypes from things that ship.

Beyond individual work, I mentor junior developers at the Elevate Web Development Club at IIIT Nagpur — covering REST API design, database modeling, async patterns, and system design fundamentals.

**Open To:** Backend Engineering Internships · AI/ML Engineering Roles · Full Stack Opportunities · Open Source Collaboration · Research Partnerships

---

## Tech Stack

<div align="center">

### Languages
[![Languages](https://skillicons.dev/icons?i=cpp,python,js,ts,sql&theme=dark)](https://skillicons.dev)

### Frontend
[![Frontend](https://skillicons.dev/icons?i=react,redux,tailwind,html,css,vite&theme=dark)](https://skillicons.dev)

### Backend & Databases
[![Backend](https://skillicons.dev/icons?i=nodejs,express,fastapi,mongodb,mysql,redis,rabbitmq&theme=dark)](https://skillicons.dev)

### Cloud, DevOps & Tooling
[![Tooling](https://skillicons.dev/icons?i=git,github,postman,linux,docker,vscode&theme=dark)](https://skillicons.dev)

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|--------|-------------|---------|
| Retrieval-Augmented Generation | Advanced | LangChain · ChromaDB · Mistral AI · semantic chunking and embedding pipelines |
| Speech-to-Text | Advanced | OpenAI Whisper · audio preprocessing · transcription at scale |
| LLM Orchestration | Advanced | LangChain chains · prompt engineering · memory management · tool use |
| Vector Databases | Intermediate | ChromaDB · embedding storage · similarity search · indexing strategies |
| Hugging Face Ecosystem | Intermediate | Model inference · transformers · pipeline API · fine-tuning fundamentals |
| AI Application Development | Advanced | Streamlit · FastAPI · end-to-end AI product delivery |

</div>

---

## Featured Projects

<details>
<summary><b>✈️ Airline Booking System — Microservices Architecture</b></summary>

<br/>

A production-grade airline reservation platform designed from the ground up as a distributed microservices system. The architecture features a dedicated API Gateway handling request routing, authentication enforcement, and rate limiting. Services communicate asynchronously through RabbitMQ, decoupling producers from consumers and enabling resilient event-driven workflows. A standalone Notification Service processes booking events from the message queue and dispatches confirmations. Data access layers are built with Sequelize ORM on MySQL, providing schema migrations and transactional integrity.

<br/>

| Attribute | Details |
|-----------|---------|
| **Stack** | Node.js · Express.js · RabbitMQ · Sequelize ORM · MySQL · JWT |
| **Architecture** | Microservices · API Gateway · Event-Driven · REST |
| **Performance** | Async inter-service messaging · decoupled notification delivery |
| **Security** | JWT authentication · gateway-level auth middleware · role-based access |
| **Impact** | Demonstrates enterprise booking system patterns applicable to high-scale travel platforms |
| **Repository** | [![GitHub](https://img.shields.io/badge/View-Repository-181717?style=flat-square&logo=github)](https://github.com/Abhinav053) |

</details>

---

<details>
<summary><b>🚗 Drivo — Real-Time Ride Sharing Backend</b></summary>

<br/>

A high-performance backend engine powering a real-time ride-matching platform. Driver proximity is computed using Redis GEO commands, enabling sub-millisecond geospatial queries to surface the nearest available drivers. Socket.IO maintains persistent bidirectional WebSocket connections between riders and drivers, broadcasting ride state transitions — request, accept, en route, completed — in real time. BullMQ manages background job queues for ride timeout handling, retry logic, and deferred notifications. The entire system is designed for concurrency, with Redis handling both caching and geospatial state.

<br/>

| Attribute | Details |
|-----------|---------|
| **Stack** | Node.js · Socket.IO · Redis · BullMQ · JWT · Express.js |
| **Architecture** | Event-driven · WebSocket · Queue-based job processing |
| **Performance** | Redis GEO for O(log N) proximity queries · persistent WS connections |
| **Security** | JWT authentication · token-scoped ride session management |
| **Impact** | Scalable ride-matching engine pattern applicable to real-time logistics and mobility platforms |
| **Repository** | [![GitHub](https://img.shields.io/badge/View-Repository-181717?style=flat-square&logo=github)](https://github.com/Abhinav053) |

</details>

---

<details>
<summary><b>🤖 AI Video Assistant — RAG Conversational System</b></summary>

<br/>

An end-to-end intelligent video Q&A system that transforms video content into a conversational knowledge base. The pipeline begins with OpenAI Whisper transcribing audio to text, which is then chunked, embedded, and persisted in ChromaDB as a vector store. At query time, a LangChain retrieval chain fetches semantically relevant transcript segments and passes them as context to Mistral AI for grounded, accurate response generation. The full system is served through a Streamlit interface, providing a clean multi-turn chat experience. This is a production-aware RAG implementation with attention to chunk sizing, retrieval precision, and context window management.

<br/>

| Attribute | Details |
|-----------|---------|
| **Stack** | Python · LangChain · OpenAI Whisper · ChromaDB · Mistral AI · Streamlit |
| **Architecture** | RAG Pipeline · Vector Store · LLM Orchestration |
| **Performance** | Semantic chunking · embedding-based retrieval · context-aware generation |
| **Security** | Local vector store · no third-party data persistence |
| **Impact** | Demonstrates applied LLM engineering with real-world RAG patterns for knowledge retrieval |
| **Repository** | [![GitHub](https://img.shields.io/badge/View-Repository-181717?style=flat-square&logo=github)](https://github.com/Abhinav053) |

</details>

---

## Experience

**Senior Core Member & Technical Mentor** — Elevate Web Development Club, IIIT Nagpur
`Jan 2024 – Present`

Leading technical mentorship initiatives for junior undergraduate developers across backend engineering and system design domains. Driving engineering culture through structured knowledge transfer, project reviews, and hands-on workshops.

- Mentoring students in REST API design, Express.js, database modeling, and asynchronous programming patterns
- Conducting sessions on system design fundamentals including caching, message queues, and microservices
- Reviewing and providing architectural feedback on student projects and capstone work
- Contributing to curriculum design for backend engineering tracks within the club

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![System Design](https://img.shields.io/badge/System%20Design-6E40C9?style=flat-square&logo=buffer&logoColor=white)
![Mentorship](https://img.shields.io/badge/Technical%20Mentorship-4F46E5?style=flat-square&logo=academia&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## Achievements

<div align="center">

| Recognition | Details |
|-------------|---------|
| LeetCode Knight ⚔️ | Peak rating **1881** · Top competitive tier on the platform |
| 1000+ Problems Solved | Consistent problem-solving across arrays, graphs, DP, trees, and system design |
| CodeChef 3-Star ★★★ | Rated competitive programmer on CodeChef |
| AlgoUniversity Bootcamp | **Ranked 17 out of 600** participants — top 3% nationally |
| ESoC Hackathon | **3rd Place** — engineering competition at IIIT Nagpur |

</div>

---



## Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-Knight%20%E2%9A%94%EF%B8%8F%20%7C%201000%2B%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com)
[![CodeChef](https://img.shields.io/badge/CodeChef-3%E2%98%85%20Rated-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://codechef.com)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://geeksforgeeks.org)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://hackerrank.com)

</div>

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Abhinav053&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=6E40C9&icon_color=6E40C9&text_color=C9D1D9&ring_color=6E40C9"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhinav053&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E40C9&text_color=C9D1D9&langs_count=8"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Abhinav053&theme=tokyonight&hide_border=true&background=0D1117&ring=6E40C9&fire=7C3AED&currStreakLabel=6E40C9&sideLabels=C9D1D9&dates=8B949E&stroke=6E40C9)](https://git.io/streak-stats)

</div>

---

## GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=Abhinav053&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Abhinav053&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=6E40C9&line=7C3AED&point=C9D1D9&area=true&area_color=6E40C9)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## Contribution Snake

<div align="center">

![Snake Animation](https://raw.githubusercontent.com/Abhinav053/Abhinav053/output/github-contribution-grid-snake-dark.svg)

</div>

---

## Current Focus

```yaml
learning:
  - Advanced distributed systems patterns (CQRS, Event Sourcing, Saga)
  - LLM fine-tuning and alignment techniques
  - Kubernetes and container orchestration at scale
  - System design for high-availability platforms

building:
  - AI-powered backend services with LangChain and FastAPI
  - Real-time systems with WebSocket and Redis pub/sub
  - RAG pipelines with production-grade retrieval strategies
  - Open source tooling for backend developers

exploring:
  - Vector database internals and approximate nearest neighbor search
  - Async Python with asyncio for high-throughput AI services
  - Edge deployment of quantized LLMs
  - GraphQL and federated API architecture

open_to:
  - Backend Engineering Internships (2025)
  - AI/ML Engineering Opportunities
  - Open Source Collaboration
  - Research Projects in Distributed AI Systems
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-Reach%20Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhinav@email.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abhinav-singh)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abhinav053)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-6E40C9?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Abhinav053)

</div>

---

<div align="center">

*"The measure of an engineer is not the complexity they introduce, but the complexity they eliminate."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6E40C9&height=100&section=footer"/>
