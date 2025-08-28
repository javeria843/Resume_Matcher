🤖 AI Resume Matcher & Job Advisor
An intelligent Streamlit-based web app that analyzes resumes against job descriptions using NLP and embeddings, then recommends missing skills and suitable roles using Gemini Pro. Built for job seekers, career coaches, and recruiters to streamline resume optimization and role matching.

🚀 Features
📄 Upload resume and job description (PDF or TXT)

🧠 NLP preprocessing with spaCy and NLTK

🔍 Semantic similarity scoring using Sentence Transformers

💡 Gemini-powered suggestions for missing skills and ideal job roles

📊 Upload history tracking with CSV logging

⚡ Fast, responsive UI with Streamlit

🧰 Tech Stack
Component	Description
Python	Core programming language
Streamlit	Interactive web interface
PyMuPDF (fitz)	PDF text extraction
spaCy + NLTK	Text preprocessing and lemmatization
SentenceTransformers	Embedding and cosine similarity
Gemini Pro	Generative AI for skill and role suggestions
dotenv	Secure API key management
pandas + csv	History storage and display
📦 Installation
bash
git clone https://github.com/yourusername/resume-matcher.git
cd resume-matcher
pip install -r requirements.txt
Create a .env file and add your Gemini API key:

env
GEMINI_API_KEY=your_api_key_here
🖥️ Usage
bash
streamlit run main.py
Upload your resume and job description.

Click Analyze to view:

Similarity score

Suggested missing skills

Recommended job roles

View your upload history at the bottom.

📁 Sample Output
Similarity Score: 0.78 ✅

Suggested Skills:

Cloud Computing

REST APIs

Agile Methodologies

Recommended Roles:

Data Analyst

ML Engineer

🧠 How It Works
Text is extracted and cleaned from uploaded files.

spaCy lemmatizes and removes stopwords.

Sentence embeddings are generated using all-MiniLM-L6-v2.

Cosine similarity compares resume vs. job description.

Gemini Pro generates skill gaps and role suggestions.

History is logged for future reference.

🛠️ To-Do / Improvements
Add multi-resume comparison

Visualize skill gaps with charts

Integrate LinkedIn scraping for job descriptions

Add authentication for user-specific history

🙋‍♀️ About the Creator
Built by Javeria Iqbal, an AI enthusiast from Karachi, Pakistan, passionate about making machine learning accessible and impactful. Currently pursuing a Bachelor's in AI at DUET, with hands-on experience in ML pipelines, deployment, and global-ready portfolio building.
DEPLOYED APP:https://projectfolder-tjxpoeqh57wwfgrmz6defd.streamlit.app/
