 AI-powered Resume Screening and Ranking System (P1)
📌 Project Overview
The **AI-powered Resume Screening and Ranking System** is designed to automate the hiring process by analyzing, screening, and ranking resumes based on predefined job requirements. This system leverages **Natural Language Processing (NLP) and Machine Learning (ML)** techniques to extract key skills, qualifications, and experiences from resumes and compare them against job descriptions.
🚀 Features
- Resume Parsing: Extracts information such as name, contact details, skills, work experience, and education.
- Keyword Matching: Compares extracted data with job descriptions to determine relevance.
- Machine Learning Ranking: Uses an AI model to rank resumes based on suitability.
- Skill Gap Analysis: Identifies missing skills required for the job.
- Web-Based Interface: Allows recruiters to upload resumes and view ranked candidates.
- Support for Multiple Formats: Handles PDFs, DOCX, and TXT resume files.
🛠️ Tech Stack
- Frontend: React.js / Angular (for UI)
- Backend: Python (Flask / FastAPI / Django)
- NLP & ML: SpaCy, NLTK, Scikit-learn, TensorFlow
- Database: PostgreSQL / MongoDB
- Storage: AWS S3 / Firebase Storage
📂 Project Structure
```
📁 ai-resume-screening
│── 📂 frontend      # React.js / Angular-based UI
│── 📂 backend       # Flask / Django backend
│── 📂 models        # Machine learning models for ranking
│── 📂 data          # Sample resumes & training data
│── 📂 utils         # Helper scripts (resume parsing, keyword extraction)
│── README.md       # Project documentation
```
🔧 Installation & Setup
1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/ai-resume-screening.git
cd ai-resume-screening
```
📊 How It Works
1. Upload Resumes 📂: Users upload resumes via the web interface.
2. Resume Processing ⚙️: The backend extracts text and key details from the resume.
3. AI Analysis🤖: The system ranks resumes based on job fit using ML models.
4. Ranked Output 📈: Recruiters receive a sorted list of candidates based on relevance.


