**📝 ATS Resume Analyzer **
An AI-powered web application that evaluates how well a resume matches a specific job description — just like an Applicant Tracking System (ATS). It uses natural language processing (NLP) and rule-based logic to generate an ATS score, highlight missing skills, and provide actionable suggestions.

🚀 Features
📄 Upload PDF resumes and parse structured data
🧠 NLP-based skill and keyword extraction using spaCy
📊 Resume scoring across 5 key dimensions:
Skills Match
Keyword Match
Content Relevance
Experience Match
Education Match
📈 Visualizations: Gauge charts, radar plots, and bar graphs
💡 Intelligent improvement suggestions
🔐 Runs locally – no data is uploaded or stored
🛠️ Technologies Used
Layer	Stack
Frontend	Streamlit
NLP & Parsing	spaCy, re, PyMuPDF
ML & Metrics	scikit-learn, TF-IDF, Cosine Similarity
Visualization	Plotly, Matplotlib, Seaborn
Automation	GitHub Actions (CI)
📦 Installation
Clone the repo and run the setup script:

git clone https://github.com/althameez-01/ATS-Resume-Analyzer-main.git
cd ATS-Resume-Analyzer-main
python run_resume_analyzer.py

## 📂 Project Structure

├── app.py                   # Main Streamlit app
├── resume_parser.py         # PDF parser and section extractor
├── job_matcher.py           # Scoring, matching logic, and suggestions
├── run_resume_analyzer.py   # Auto-installer and launcher
├── requirements.txt         # Dependencies
├── .github/workflows/README.yml # GitHub Actions workflow
└── README.md
