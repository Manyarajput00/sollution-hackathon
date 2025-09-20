LegalAI — Demystifying Legal Documents

AI-powered tool to simplify legal documents, highlight risky clauses, and provide interactive Q&A. Built for the GenAI Exchange Hackathon.


---

📌 Overview

LegalAI simplifies legal documents (rental agreements, loan contracts, Terms of Service, etc.) into plain language, highlights risky clauses with clause-level alerts, and offers an interactive chatbot for clarifications.


---

🚩 Problem Statement

Legal documents are often full of jargon and hard to understand.

Information asymmetry causes users to unknowingly accept unfair terms.

This leads to financial and legal risk for everyday users.

There is no affordable, AI-first solution targeted at non-expert users.



---

🎯 Objective

Simplify contracts into plain, user-friendly language.

Automatically highlight risky clauses and provide risk ratings.

Offer interactive Q&A via a chatbot to clarify user questions.

Provide a privacy-first, safe-first point of contact before legal consultation.



---

💡 Unique Selling Points (USP)

Plain-language summaries of contracts.

Clause-level risk alerts and ratings.

AI chatbot for instant user support.

Visual contract navigator (future enhancement).

Privacy-first processing and secure storage.



---

🔑 Features

Upload a contract → receive an instant summary.

Clause-by-clause risk rating and highlights.

Interactive AI chatbot for follow-up questions.

Contract comparison (planned future feature).

Multilingual support for wider adoption.



---

🔄 Process Flow

1. User uploads the legal document (PDF/DOC).


2. System extracts and segments text into clauses.


3. GenAI (Vertex AI / Hugging Face models) summarizes and classifies clauses.


4. Risky terms are detected and highlighted with ratings.


5. User explores the visual navigator and interacts with the chatbot.




---

🏗️ Architecture (Low-Cost Setup)

Frontend: Streamlit or Softr (free tiers)

Backend: Firebase + Cloud Run (free tier)

AI/ML: Vertex AI (free credits) / Hugging Face models

Parsing: PyPDF2, LangChain

Storage: Firestore (free tier)

Security: GCP IAM & encryption



---

🛠️ Technologies Used

GenAI: Vertex AI or Hugging Face

NLP: spaCy, LangChain

Frontend: Streamlit, Softr

Backend: Firebase, Cloud Run

Storage & Tools: Firestore, GitHub, Loom/OBS



---

💰 Cost & Feasibility

Google Cloud free tier ($300 credits)

Hugging Face free models and OSS libraries

Firebase / Vercel free hosting for MVP

Overall: low-cost / near-zero MVP



---

📊 Evaluation Alignment

Technical Merit (40%) — GenAI + NLP pipeline

User Experience (10%) — clean, plain-language UI

Alignment with Cause (15%) — legal accessibility

Innovation (20%) — clause risk alerts + navigator

Market Feasibility (15%) — SaaS / freemium



---

🚀 Future Scope

Contract comparison and side-by-side diffs

Rich visual dashboard for contract navigation

Local language support and regional legal templates

Lawyer referral / escalation workflow



---

📌 How to Run (Prototype)

Quick start for the hackathon prototype:

1. Clone repository


2. pip install -r requirements.txt


3. streamlit run app.py


4. Upload a legal doc (PDF)


5. Interact with chatbot and view summaries/risk alerts




---

👥 Team

Team Name: Team_202_

Team Leader: Manya Rajput 

Members: Manya Rajput,Manu Dev,Anjali,    Muskan Katyal 



---

📽️ Demo

Record a short Loom/OBS video demo and attach the link here for judges.


---

📜 License

This project is open-source under the MIT License.


---

Prepared for GenAI Exchange Hackathon • LegalAI
