# 🎓 ACES: Adaptive Concept Evaluation System

**🤖 AI-Driven Conceptual Assessment Platform & SOC**

ACES (Adaptive Concept Evaluation System) is an AI-powered educational platform designed to replace static testing with deep semantic analysis. By utilizing Multi-Agent NLP workflows and Large Language Models (LLMs), the system dynamically adjusts scenario-based problem difficulty in real-time, isolating actual conceptual mastery from mere grammatical structure. 🚀

---

## 🎯 Core Objectives

*   🧠 **Assess True Understanding:** Evaluates logical reasoning and knowledge transfer over rote memorization, moving beyond standard MCQs and literal string-matching heuristics.
*   🔍 **Semantic Evaluation:** Implements NLP techniques to extract and reliably evaluate the semantic meaning of open-ended, descriptive answers using strictly grounded educational rubrics.
*   📈 **Dynamic Difficulty Scaling:** Automates adaptive questioning using a multi-agent engine governed by Item Response Theory (IRT) to recalibrate question complexity based on real-time performance and prevent testing fatigue.
*   📊 **Diagnostic Analytics:** Provides educators with a real-time analytics dashboard featuring a multi-dimensional "Understanding Index" to identify granular class learning gaps.

---

## 🏗️ System Architecture

The ACES platform is built on a robust, multi-tiered architecture:

1.  🖥️ **Presentation Layer (Client Tier):**
    *   Material Upload & Assessment UI
    *   Student Dashboard (Progress & Analytics)
    *   Corrective Feedback & Recommendations
2.  ⚙️ **Application Layer (ACES Core Logic):**
    *   Document Parser & Chunking Module
    *   Multi-Agent LLM Orchestrator
    *   Semantic Evaluator & Fault Analyzer
    *   Dynamic Question Generation Engine
    *   Adaptive Study Recommendation Engine
3.  🗄️ **Data Persistence Layer:**
    *   Vector Database (Embeddings)
    *   Relational DB (User Profiles)
    *   Analytics & Fault Logs

---

## 📚 Academic Foundation

This project is built upon the synthesis of 25 recent (2025–2026) research papers on AI in educational assessment. The core methodology extends the framework proposed in *"LLM-as-Judge in Education: A Curriculum-Grounded Marking Pipeline"* (Xu et al., 2026) by integrating dynamic difficulty scaling to overcome the limitations of static testing.

---

## 👥 Project Team (Group 1)

**👨‍💻 Developers:**
*   Ananthu A R (LPRP23CS090)
*   Muhammed Shafi A S (PRP23CS059)
*   Madhav R (PRP23CS055)
*   Hasna Sharin C K (PRP23CS044)

**👩‍🏫 Project Guidance:**
Ms. Smitha M Jasmine

**🏫 Institution:**
Department of Computer Science, Cape College of Engineering, Alappuzha

---

## 🛠️ Setup and Installation

```bash
# Clone the repository
git clone [https://github.com/yourusername/aces-evaluation-system.git](https://github.com/yourusername/aces-evaluation-system.git)
cd aces-evaluation-system

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Set up environment variables (API keys, Database URIs)
cp .env.example .env

# Run the application
python run.py
