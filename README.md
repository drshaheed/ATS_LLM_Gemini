Based on the content of the `app.py` file, here's a project description you can use for your GitHub repository:

---

## Smart ATS (Applicant Tracking System)

Smart ATS is a Streamlit-based web application designed to assist job seekers in optimizing their resumes for Applicant Tracking Systems (ATS) commonly used in the tech industry. This application leverages the capabilities of Google's Generative AI, specifically the Gemini-Pro model, to evaluate resumes against job descriptions and provide valuable feedback.

### Features

- **Resume Evaluation:** Users can upload their resumes in PDF format, and the application will evaluate them against a provided job description.
- **ATS Compatibility:** The evaluation is based on criteria important for ATS, focusing on the tech field, software engineering, data science, data analyst, and big data engineer roles.
- **Feedback:** The application provides a percentage match based on the job description, lists missing keywords, and offers a profile summary to help users improve their resumes.

### How It Works

1. **Job Description Input:** Users paste the job description into the provided text area.
2. **Resume Upload:** Users upload their resume in PDF format.
3. **Evaluation:** Upon submission, the application processes the resume and job description, providing feedback on how well the resume matches the job description and suggesting improvements.

### Technology Stack

- **Frontend:** Streamlit
- **Backend:** Google Generative AI (Gemini-Pro model)
- **Language:** Python
- **Libraries:** PyPDF2, dotenv

### Setup and Installation

1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`
3. Set up your Google API key in the `.env` file.
4. Run the application: `streamlit run app.py`

### Usage

Access the web application locally by navigating to `http://localhost:8501` in your web browser.

---

Feel free to modify this description to better suit your project or add any additional details you think are important!
