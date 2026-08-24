


### 👋 ¡Hola, soy KIMRAHUI!

<div align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2tlMnN5MDJ4Z2RjczFuNG5icG11eWprcmFqaGNleWF0Nzl2NzNwYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Basrh159dGwKY/giphy.gif" width="95%" />
</div>

---

### About Me & Key Projects

- 💻 **Certifications**
  - Information Processing Industrial Engineer
  - Web Design Craftsman
  - SQL Developer (SQLD)
  - Google Analytics IQ
  - 2x Claude Course Completions (Building with the Claude API & Model Context)

- 📂 **Key Projects & Technical Case Studies**
  - 🎧 **`SunoSync AI`** — End-to-End AI & Audio Visual Web OS SaaS
    - *Description*: An AI-driven audio-visual SaaS platform integrating multimodal audio spectrum analysis, Open-CLAP 1024-dim vector search, lyrics-based RAG copywriting, and real-time 60fps Web Audio visualizers.
    - ⚡ **3000px HD Cover Generation (60x Speedup: `1,500ms` ➔ `25ms`)**
      - *Problem*: 9M pixel iteration created a 1.5s computation bottleneck and CPU overload.
      - *Solution*: Replaced Python nested `for` loops with **NumPy `ogrid` C-level matrix broadcasting**.
      - *Impact*: Reduced latency from **1,500ms to 25ms (98.3%↓)** for real-time rendering.
    - 🚀 **Audio Analysis & Waveform Pipeline (20x Speedup: `3.1s` ➔ `0.18s`)**
      - *Problem*: Full MP3 re-encoding via FFmpeg and triple redundant decoding caused a 3.1s response delay.
      - *Solution*: Replaced re-encoding with `shutil.copyfile` instant copy (0.001s) and reused single in-memory decoded audio objects.
      - *Impact*: Cut response time from **3.1s to 0.18s (94.2%↓)** and reduced CPU decoding by **66.7%**.

  - 🚗 **`car` (COMMIT CAR)** — End-to-End AI Vehicle Inspection & Reservation System
    - *Description*: Full-stack platform combining Spring Boot, React, and Python FastAPI for AI-powered tire wear & defect diagnosis (VGG19), LLM vehicle advisory (Groq Llama 3/4), repair shop navigation, and reservation management.
    - *Key Highlights*: Designed transaction-safe state management (`ACTIVE` ➔ `CANCELLED` soft delete for 100% data consistency) and optimized AI serving by pinning VGG19 weights in memory for high availability.

  - 🛍️ **`cors` (Connecting to Style RoadShop)** — O2O RoadShop Digital Transition & Management Platform
    - *Description*: Digital bridge platform connecting local boutique roadshops with consumers, featuring store reservation/pickup, Toss Payments integration, seller revenue analytics, and RBAC security.
    - *Key Highlights*: Developed seller revenue analytics combining order and reservation domains via MyBatis Dynamic SQL, implemented profanity pre-filtering for review management, and established 3-tier RBAC access control.

  - ☕ **`study-bbs`** — Spring Boot Community Bulletin Board
    - *Description*: Backend community board system built with Spring Boot, implementing RESTful API endpoints, MVC architecture, Spring Security authentication, and persistent CRUD operations.

  - 📚 **`IT-Note`** — Technical Knowledge Base & Engineering Archive
    - *Description*: Curated knowledge base archiving computer science fundamentals, troubleshooting retrospectives, and daily technical learnings.

### 🌟 Vision & Cheer-Leader Developer

- 💡 **Tech for Inclusion:**   
Deeply interested in building functional features and platforms dedicated to digital inclusion and those who need technical support.
- 📣 **Cheer-Leader Vibe:**   
Passionate about fostering great collaboration by breaking down barriers and empowering teammates to create a positive synergy together.

