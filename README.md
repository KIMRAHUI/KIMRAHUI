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
      - Replaced physical `DELETE` on reservation cancel with an `ACTIVE` ➔ `CANCELLED` state transition under `@Transactional`, fixing broken references and keeping full cancellation history.
      - Fine-tuned an ImageNet-pretrained VGG19 to overcome overfitting on a small tire dataset, and moved model loading to server startup so weights load once instead of per request, which stopped the AI server from crashing under consecutive uploads.

  - 🛍️ **[`cors` (Connecting to Style RoadShop)](https://github.com/KIMRAHUI/cors)** — O2O Roadshop Digital Transition & Management Platform
    - *Description*: Platform connecting local boutique roadshops with consumers, featuring store reservation/pickup, Toss Payments integration, seller revenue analytics, and role-based access control.
    - *Key Highlights*: Built seller revenue analytics joining the order and reservation domains with MyBatis Dynamic SQL, added profanity pre-filtering for reviews, and set up 3-tier RBAC (customer / seller / admin).

  - 📚 **[`IT-Note`](https://github.com/KIMRAHUI/IT-Note)** — Technical Knowledge Base
    - *Description*: Personal archive of CS fundamentals, troubleshooting notes, and daily learnings, written to explain *why* the code works rather than just copying it.

  - ☕ **[`study-bbs`](https://github.com/KIMRAHUI/study-bbs)** — Spring Boot Bulletin Board (Learning Project)
    - *Description*: Study project for Spring Boot MVC fundamentals using MyBatis and Thymeleaf: layered Controller ➔ Service ➔ Mapper structure, user login, post & comment CRUD, and request interceptors.

### 🌟 Vision & Cheer-Leader Developer

- 💡 **Tech for Inclusion:**  
Deeply interested in building functional features and platforms dedicated to digital inclusion and those who need technical support.
- 📣 **Cheer-Leader Vibe:**  
Passionate about fostering great collaboration by breaking down barriers and empowering teammates to create a positive synergy together.
