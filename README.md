# AI Resume Matcher & Skill Gap Analyzer

__Project Statement__ : 

Recruiters spend hours screening resumes for job descriptions. Manual screening is inefficient and subjective. 
This project automates resume matching and helps candidates understand how to improve their applications.

This project helps match resumes to job descriptions using NLP techniques. 
It not only calculates a semantic match score but also provides detailed skill gap analysis 
and actionable suggestions to improve the resume.

__Solution overview__ :
- Extracts text from PDF resumes
- Cleans text for NLP processing
- Converts resume and job description into embeddings for semantic matching
- Extracts skills from resume and job description
- Compares skills to identify missing or extra skills
- Generates actionable resume improvement suggestions
- Provides a final match score and recommendation level (Strong / Moderate / Weak)

__Tools & Technologies__ : 
- Python
- PyMuPDF (PDF text extraction)
- Sentence Transformers (NLP embeddings)
- scikit-learn (similarity calculation)

__Procedure__ : 
1. Upload a PDF resume
2. Convert resume text into lowercase and clean formatting
3. Convert resume and job description text into embeddings
4. Compute cosine similarity to get match score
5. Extract skills from resume and job description
6. Identify missing and extra skills
7. Generate improvement suggestions based on missing skills and match score

__Example Output__ :

Match Score: 68%

Match Level: Moderate Match

Matching Skills: Python, Pandas, NumPy

Missing Skills: SQL, NLP, Machine Learning

Suggestions:

1. Add projects or experience relevant to the job description.
   
2. Add or highlight these skills in your resume: SQL, NLP, Machine Learning


__Further Improvements__ :
- Add Streamlit UI for interactive use
- Include section-wise matching (skills, experience, education)
- Allow batch processing of multiple resumes
- Suggest relevant projects or certifications automatically









