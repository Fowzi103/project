AI-Powered Resume Ranker

Welcome to the **AI-Powered Resume Ranker** — a smart tool that helps you automatically rank resumes based on their match to a job description!  

No more manual shortlisting — let AI do the heavy lifting so you can focus on the best candidates.  

What does it do?
✅ You paste a job description  
✅ The app reads and analyzes resumes  
✅ It calculates how well each resume matches the job  
✅ It shows you the top resumes  
✅ You can download a ranked report for HR  

How it works
🔹 The app uses **natural language processing (NLP)** to clean and understand the text  
🔹 It turns resumes + job description into numeric features (TF-IDF)  
🔹 It computes **cosine similarity** between resumes and the job description  
🔹 Ranks resumes from most to least relevant  

Tools & Libraries
- Python
- Streamlit – web app interface  
- Pandas – data handling  
- SpaCy – text preprocessing  
- scikit-learn – TF-IDF + similarity  

How to run the app

First install the dependencies:  
`bash
pip install streamlit pandas spacy scikit-learn
python -m spacy download en_core_web_sm

Why use this tool?
✅ Save time on resume screening
✅ Get a data-driven shortlist
✅ Easy to use interface
