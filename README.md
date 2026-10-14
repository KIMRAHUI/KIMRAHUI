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
  - 🚗 **[`car` (COMMIT CAR)](https://github.com/KIMRAHUI/car)** — AI Vehicle Inspection & Repair Reservation Platform
    - *Description*: Solo full-stack project (74 days) combining Spring Boot, React, and Python FastAPI for AI-powered tire wear diagnosis (VGG19), LLM vehicle advisory (Groq Llama), repair shop search, and reservation management. Deployed on GCP behind Nginx and Cloudflare.
    - *Key Highlights*:
      - Replaced physical `DELETE` on reservation cancel with a `CANCELED` status update under `@Transactional`, fixing broken references and keeping full cancellation history.
      - Secured the reservation API by checking ownership against the logged-in session user, so users can no longer view or cancel other people's reservations by changing an email or ID.
      - Fine-tuned an ImageNet-pretrained VGG19 to overcome overfitting on a small tire dataset, and moved model loading to server startup so weights load once instead of per request, which stopped the AI server from crashing under consecutive uploads.

  - 🛍️ **[`cors` (Connecting to Style RoadShop)](https://github.com/KIMRAHUI/cors)** — O2O Roadshop Reservation & Sales Management Platform (Team of 3)
    - *Description*: Platform connecting local boutique roadshops with consumers, featuring store reservation/pickup, Toss Payments, seller revenue analytics, and staff permission management.
    - *My Role*:
      - Built seller revenue analytics combining the order and reservation domains with MyBatis Dynamic SQL.
      - Implemented a 3-step review trust flow: reviews only after purchase confirmation ➔ profanity filter ➔ user reports & admin review.
      - Designed 3-tier staff RBAC (master / manager / staff) enforced in a Validator layer.

  - 🧠 **[`my-brain` (My Second Brain)](https://github.com/KIMRAHUI/my-brain)** — RAG Study Assistant Built on My Notion Notes
    - *Description*: Personal chatbot that syncs my Notion study notes to GitHub daily via GitHub Actions and answers questions grounded in those notes with LlamaIndex and Gemini. Chat history is stored in Supabase, so it works across refreshes and on mobile.
    - *Key Highlights*: Stopped full re-embedding on every restart by backing up the index to Supabase Storage and re-embedding only changed notes. Handles free-tier API quota limits with backoff retries and per-document checkpoints, so an interrupted build resumes where it stopped.

  - ☕ **[`study-bbs`](https://github.com/KIMRAHUI/study-bbs)** — Spring Boot Bulletin Board (Learning Project)
    - *Description*: Study project for Spring Boot MVC fundamentals using MyBatis and Thymeleaf: layered Controller ➔ Service ➔ Mapper structure, user login, post & comment CRUD, and request interceptors.

### 🌟 Vision & Cheer-Leader Developer

- 💡 **Tech for Inclusion:**  
Deeply interested in building functional features and platforms dedicated to digital inclusion and those who need technical support.
- 📣 **Cheer-Leader Vibe:**  
Passionate about fostering great collaboration by breaking down barriers and empowering teammates to create a positive synergy together.
