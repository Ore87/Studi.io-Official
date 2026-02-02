# Studi.io 🎓

> **Your AI-Powered Ethical Study Companion.**
> *Turning passive reading into active mastery.*

![Status](https://img.shields.io/badge/Status-Live-success)
![Stack](https://img.shields.io/badge/Stack-React_|_Supabase_|_OpenAI-blue)
![Sponsors](https://img.shields.io/badge/Powered_By-ElevenLabs_|_Daytona_|_Saily-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

##  Live Demo
Watch the full project walkthrough on YouTube:

[![Studi.io Demo](https://img.youtube.com/vi/NCUOc3zGNYo/0.jpg)](https://youtu.be/NCUOc3zGNYo)

**🔗 Try the App:** [https://studiio-seven.vercel.app](https://studiio-seven.vercel.app)

---

## Overview

**Studi.io** is an intelligent EdTech platform designed to tackle the root cause of examination malpractice: **lack of confidence and understanding.**

Unlike generic AI tools, Studi.io uses **RAG (Retrieval-Augmented Generation)** to ground its answers strictly in the student's own lecture notes and handouts. It transforms static PDFs into interactive 24/7 tutors, generates custom diagrams for visual learners, and enforces active recall through automated quizzes.

---

##  Key Features

###  1. Grounded Document Chat (RAG)
* **Context-Aware:** Upload your specific course PDFs. The AI reads *your* material, not just the internet.
* **Citations:** Every answer references specific pages in your handouts, ensuring accuracy and trust.

###  2. The Quiz Arena
* **Active Recall:** Automatically generates Multiple Choice and Theory questions from your uploaded notes.
* **Immediate Feedback:** Get instant corrections and explanations for every wrong answer.

### 3. Visual Intelligence Studio
* **Text-to-Diagram:** Struggling to understand a complex concept? Studi.io instantly generates charts, mind maps, and flowcharts to explain it visually.

###  4. Study Goals & Analytics
* **Gamified Progress:** Track learning streaks, set daily goals, and visualize your mastery over time.

---

##  Technology Stack & Sponsor Integrations

Studi.io was built using a robust modern stack, powered by cutting-edge tools provided by our hackathon sponsors:

### **Core Architecture**
* **Frontend:** React, Tailwind CSS, Lucide React
* **Backend:** Supabase (Auth, Database, Storage)
* **Deployment:** Vercel

### **AI & Voice Engine**
* **OpenAI GPT-4o:** Primary reasoning engine for document analysis.
* **🎙️ ElevenLabs:** Powers the "Audio Study Mode," converting text-based notes into realistic AI speech for on-the-go learning.
* ** Nexos.ai:** Utilized for advanced model inference and intelligent agent processing within the chat interface.
* ** KrosAI:** Integrated to handle specialized specialized AI tasks and study pattern recognition.

### **Infrastructure & Dev Tools**
* ** Daytona:** Used as the primary **Cloud Development Environment (CDE)** to accelerate the coding workflow and standardize the dev environment.
* ** Saily:** Integrated to test and ensure global connectivity and accessibility for students in different regions.
* ** .cv Domain:** The project utilizes the `.cv` domain identity for professional branding.

---


##  Getting Started (Run Locally)

If you want to run this project locally, follow these steps:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/Ore87/studi-io.git](https://github.com/Ore87/studi-io.git)
    cd studi-io
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Set up Environment Variables**
    Create a `.env` file in the root directory and add your keys:
    ```env
    VITE_SUPABASE_URL=your_supabase_url
    VITE_SUPABASE_ANON_KEY=your_supabase_key
    VITE_OPENAI_API_KEY=your_openai_key
    ```

4.  **Run the development server**
    ```bash
    npm run dev
    ```

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new features, feel free to open an issue or submit a pull request.

---

##  Contact

**Lead Developer:** Oreoluwa
* **GitHub:** [@Ore87](https://github.com/Ore87)
* **Email:** austineoreoluwa@gmail.com

---

Made with ❤️ for Students everywhere.
