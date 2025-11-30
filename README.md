# Enterprise Hiring Co-Pilot 🤖

**Multi-Agent HR Automation & Candidate Ranking System**  

---

## 🚀 Project Overview
**Enterprise Hiring Co-Pilot** is an autonomous, multi-agent HR system designed to transform traditional hiring workflows. It automates resume parsing, candidate ranking, and interview recommendations using AI-powered agents. This system helps recruiters save time, reduce bias, and make data-driven hiring decisions.

---

## 📌 Problem Statement
Recruiters often spend hours manually reviewing resumes and shortlisting candidates. Human errors and bias can also affect decision-making. The challenge is to **automate candidate screening and ranking** efficiently while maintaining accuracy and fairness.

---

## 🤖 Why Agents?
- Agents allow **modular, specialized tasks**: resume parsing, scoring, ranking, and reporting.
- Multi-agent architecture enables **parallel processing** of candidates.
- Agents can continuously improve using **feedback loops** from recruiters.

---

## 🏗️ What You Created
- **Root Orchestrator Agent:** Manages workflow and delegates tasks to sub-agents.
- **Parser Agent:** Extracts structured information from resumes (PDF, DOCX).
- **Scoring & Ranking Agent:** Evaluates candidates against job requirements.
- **Dashboard/Reports:** Presents top candidates, skills, and insights in a concise view.

**High-Level Architecture:**  

Recruiter Input → Orchestrator → Parser Agent → Ranking Agent → Dashboard/Output


---

## 🎬 Demo
- Upload resumes (PDFs)
- Provide Job Description
- Run system to get **Top N Candidates** ranked by skill match and experience
- Output includes **score, key skills, and summary** for each candidate

Example Output:

🏆 Top 3 Candidates:

1. Jeane Schme | Score: 0.9
2. RAHUL KHANNA | Score: 0.85
3. Christa Frank | Score: 0.7


---

## 🛠️ The Build
**Technologies & Tools:**
- Python 3.x
- Libraries: `json`, `pandas`, `docx`, `pptx`, `Gemini API` (for LLM parsing)
- Multi-agent orchestration
- Resume parsing & ranking logic

**Steps:**
1. Parse resumes using `Parser Agent`
2. Extract skills, experience, education
3. Score candidates using ranking agent
4. Output JSON & dashboard with top-ranked candidates

---

## 🔮 Future Enhancements
- Add **auto-interview scheduling** agent
- Integrate **ATS systems** for live data feed
- Add **feedback loop** for AI to learn recruiter preferences
- Include **bias detection** and fairness scoring

---

## 📂 Files Included
- `Enterprise_Hiring_CoPilot.ipynb` → Main Notebook
- `final_resume_ranking.json` → Sample output
- `README.md` → Project description
- Optional: sample resumes (PDF/DOCX) for testing

---

## 📎 Links
- Kaggle Notebook: [Link to your notebook]  
- Demo / Writeup: [Kaggle Writeup URL]

---

## ✅ Conclusion
Enterprise Hiring Co-Pilot automates resume screening and ranking using a **multi-agent AI system**. It reduces manual work, ensures data-driven hiring, and provides top candidate recommendations efficiently.


