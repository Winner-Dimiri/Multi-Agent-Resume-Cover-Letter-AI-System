# Multi-Agent-Resume-Cover-Letter-AI-System
A Cutting-Edge AI System that generates tailored graduate trainee resumes and compelling cover letters using **multi-agent orchestration**. Built with **CrewAI**, this system leverages **AI-driven profiling, research, resume strategy, formatting, and cover letter generation to produce ATS-compliant, personalized, and recruiter-ready applications.

## Overview

This project demonstrates a **real-world AI workflow** for **graduate trainee applications**:

- **Profiler Agent:** Extracts applicant info from CVs and GitHub profiles.
- **Research Agent:** Gathers job requirements and hidden traits from company postings.
- **Resume Strategist Agent:** Tailors resumes to highlight **academic achievements, leadership potential, and key skills**.
- **Resume Formatter Agent:** Produces **ATS-friendly, structured, and visually appealing resumes**.
- **Cover Letter Specialist Agent:** Creates **personalized, compelling, keyword-optimized cover letters**.

The system ensures **maximum alignment with graduate trainee program requirements** and **optimizes the chances of getting interview calls**.

## Key Features

- **Multi-Agent Architecture:** Orchestrates multiple AI agents for specialized tasks.
- **ATS Optimization:** Keyword-aware, structured resumes and cover letters.
- **Personalization:** Custom-tailored content using applicant profiles.
- **File Outputs:** Generates resumes and cover letters in Markdown or text formats.
- **Extensible Tools:** Integrates **web scraping, semantic search, and file reading** tools.
- **Graduate Trainee Focused:** Specifically optimized for structured trainee programs and early career roles.

## Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/<username>/resume_crew.git
cd resume_crew

2. **Install Dependencies**
pip install -r requirements.txt

python src/main.py

3. **Run the System**
python src/main.py

4. **Outputs**

---

### **Project Structure (Visual Overview)**
```markdown
## Project Structure
resume_crew/
├─ config/ # Agent and task YAML files
├─ src/ # Python scripts
├─ tools/ # Optional helper tools
├─ output/ # Agent outputs
├─ data/ # Example inputs
└─ docs/ # Documentation and workflow visuals

**Usage/Example**
## Usage Example

1. Place applicant's resume in `data/fake_resume.md`.
2. Provide GitHub profile URLs or personal write-ups.
3. Run `python src/main.py`.
4. Check the `output/` folder for:
   - Tailored resume (Markdown or text)
   - Compelling, personalized cover letter




