# AI Resume Analyzer

## About the Project
AI Resume Analyzer is a web application developed using Python and Django. It helps users analyze their resumes, extract skills, and compare them with job role requirements. It highlights matching skills, missing keywords, and a match percentage to help users identify areas for improvement.

## Features
- User registration and login
- Upload resumes in PDF, DOCX, and TXT formats
- Extract skills from resume text
- Compare resume skills with job role requirements
- Display job matching scores and missing skills
- Create and update user profiles
- View uploaded resume history
- Delete uploaded resumes
- Add and manage job roles

## Technologies Used
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python, Django
- **Database:** SQLite
- **Libraries:** PyPDF2, python-docx

## Installation and Setup

1. Clone this repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project folder:

   ```bash
   cd resumeskill
   ```

3. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

4. Activate the virtual environment.

   **Windows:**
   ```bash
   .venv\Scripts\activate
   ```

5. Install the required packages:

   ```bash
   python -m pip install -r requirements.txt
   ```

6. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

7. Start the development server:

   ```bash
   python manage.py runserver
   ```

8. Open your browser and visit:

   `http://127.0.0.1:8000/`

## How It Works
1. Register or log in to your account.
2. Upload your resume.
3. The application extracts readable text and identifies skills using keyword matching.
4. Select or compare your skills against a job role.
5. Review the matching percentage and missing skills.
6. Use the results to improve your resume.

## Future Improvements
- Integrate an AI or NLP model for more advanced resume analysis.
- Add OCR support for scanned resumes.
- Recommend suitable job roles based on skills and qualifications.
- Improve resume feedback and keyword recommendations.

## Limitations
- Skill extraction currently relies on keyword matching.
- Scanned PDFs may not work correctly without OCR support.
- Matching scores are basic estimates and do not guarantee job suitability.

## Author
**Aishwarya M.**  
BCA Graduate | Aspiring Software Developer

