# Hi, I'm Sanaya 👋

I am a software developer focused on turning machine learning concepts and raw logic into functional, end-to-end web applications. Rather than treating ML as isolated notebook experiments, I approach projects from a software engineering perspective building clean backend logic, structuring databases, and packaging everything into usable interfaces.

### 🛠 Tech Stack & Tools

* **Languages & Web:** Python, Java, JavaScript, Vue.js, Flask, Jinja2, HTML/CSS
* **Data & Machine Learning:** Scikit-Learn, Pandas, NumPy, Feature Engineering
* **Backend & Workflow:** REST APIs, PostgreSQL, SQLite, Redis, Celery
* **AI:** Gemini API, Ollama (Qwen · Yi), Python ast module
* **Tools:** Git, GitHub

---

### 📂 Projects

#### 🏔️ TrekMate
*Trekking Management System*
* Vue.js SPA talking to a Flask REST API making a system to replace spreadsheet coordination for adventure agencies.
* Handles automated email reminders, report generation, and on-demand CSV exports with real-time status polling.
* Three Celery tasks run on schedule: daily email reminders, monthly business reports. Redis handles the Celery broker and API response caching, with cache invalidation on every booking event.

#### 🛡️ PyLens
*Multi-Provider Python Code Review Tool*
* Combines offline AST-based static analysis with concurrent reviews from LLM providers (Qwen, Yi, Gemini).
* Findings are deduplicated across providers, tagged with cross-provider consensus counts, cached by SHA-256 code hash, and provider failures are isolated so one broken API never affects the rest of the review.


#### 🎓 Campus Recruitment Portal
*Placement System with Algorithmic Fit Scoring*
* Three-role system (Admin, Student, Company) with a custom weighted heuristic fit-score engine, rather than a black-box model.
* Assigns candidate weighting based on core competencies and applies academic thresholds for clear evaluation.

---

### 🧪 Currently Exploring
* Building RAG (Retrieval-Augmented Generation) pipelines for PDF document query and search.

---

📫 **Connect:** [LinkedIn](https://www.linkedin.com/in/sanayaranjit) | sanayaranjit@gmail.com
<!--
**sanayaranjit/sanayaranjit** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
