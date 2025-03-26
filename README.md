# 🚀 GEN AI Document Classification System

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
A Gen AI Document Classification System is an AI-powered solution that automatically analyzes, categorizes, and organizes documents based on their content, structure, and context. Utilizing natural language processing (NLP) and machine learning, the system can classify documents into predefined categories Adjustment, AU Transfer, Closing Notice, Commitment Change, Fee Payment, Money Movement-Inbound, Money Movement-Outbound. It can extract key information, detect document intent, and in future route files to the appropriate workflows. This enhances efficiency, improves document retrieval, and streamlines business processes by reducing manual sorting and classification efforts.

## 🎥 Demo
🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots:

![Screenshot 1](link-to-image)

## 💡 Inspiration
1. Automation & Efficiency:
Businesses receive vast amounts of emails and documents daily. Manually sorting them is time-consuming and prone to errors. AI-powered classification automates this process, reducing workload and improving response times.

2. Advancements in NLP & AI:
With breakthroughs in Natural Language Processing (NLP) and transformer models (e.g., GPT, BERT), AI can now understand context, intent, and semantics, enabling accurate classification and routing.

3. Compliance & Risk Management:
Many industries (finance, healthcare, legal) require proper document handling for compliance. AI ensures documents are categorized correctly, reducing regulatory risks and audit errors.

4. Enhanced Customer Experience:
Faster email triage means quicker responses to customer inquiries, leading to better satisfaction and engagement.

5. Integration with Workflow Systems:
AI-classified documents can be seamlessly integrated with CRM, ERP, and ticketing systems to automate business workflows.

6. Scalability & Cost Reduction:
AI-driven classification scales effortlessly with business growth, reducing dependency on manual labor and cutting operational costs.

## ⚙️ What It Does
Explain the key features and functionalities of your project.

## 🛠️ How We Built It
* Frontend: React for building an interactive UI, Lucide React for icons, and Tailwind CSS for responsive and modern styling.
* Backend: FastAPI for building high-performance APIs, running on Uvicorn as the ASGI server.
* Database: PostgreSQL for efficient storage, retrieval, and management of classified emails and documents.
* LLM APIs: Integration with OpenAI, GEMINI, DeepSeek, or Hugging Face models for advanced text analysis, classification, and intent detection.

## 🚧 Challenges We Faced
1. Doing NER on the input which requires context to reduce load on llm.
2. API limits exhausted, limiting the acceptance testing.
3. Writing robust test cases.
4. Balancing work and hackathon coding.


## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/gaied-hackstreet-boyz.git
   ```
2. Install dependencies  
   ```sh
   Install docker. Make sure docker destop or daemon is running.
   Make sure latest Python version is installed and added to PATH
   Install VScode or any favorite IDE which supports both Python and Javascript libraries. 
   ```
3. Run the project  
   ```sh
   # First time running or new python module has been added to requirements
   docker-compose up --build
   # Minor changes to file:
   docker-compose up --force-recreate
   Once the all the services are up, you can access http://localhost:3000/ from your favorite browser to view the landing page
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: React + lucide react + Tailwind css
- 🔹 Backend: FastAPI + uvicorn
- 🔹 Database: PostgreSQL
- 🔹 LLM APIs: OpenAI / GEMINI / DeepSeek / HuggingFace 

## 👥 Team
- **Himesh Maniyar** - [GitHub](https://github.com/Himesh-29) | [LinkedIn](https://www.linkedin.com/in/himesh-maniyar/)
- **Abijith M G** - [GitHub](https://github.com/abijithmg) | [LinkedIn](https://www.linkedin.com/in/abijithmg/)
