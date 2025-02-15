# SmartCV-Analyzer
An AI-powered resume analysis tool that evaluates key insights and provides an ATS compatibility score using LLM.
# SmartCV Analyzer

## 📄 Tailor Your Resume for ATS Success

SmartCV Analyzer is an AI-powered resume analysis tool that helps job seekers optimize their resumes for ATS (Applicant Tracking System) compliance. It evaluates resume alignment with job descriptions, identifies missing keywords, and provides tailored improvement suggestions using **Google Gemini AI**.

---

## 🚀 Features

- **ATS Score Calculation**: Provides a match percentage between the resume and job description.
- **Keyword Analysis**: Detects missing keywords that could enhance ATS compatibility.
- **Resume Insights**: Generates a professional summary based on resume content.
- **Interactive UI**: Built using **Streamlit** for an intuitive user experience.

---

## 📌 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/SmartCV-Analyzer.git
   cd SmartCV-Analyzer
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your environment variables**:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     GOOGLE_API_KEY=your_api_key_here
     ```

---

## 🛠 Usage

1. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

2. **Upload your resume (PDF format)**.
3. **Paste the job description**.
4. **Click 'Analyze Resume' to get your ATS Score and recommendations!**

---

## 📂 Project Structure
```
SmartCV-Analyzer/
│── helper.py             # Helper functions for API calls & processing
│── app.py                # Main Streamlit application
│── requirements.txt      # Python dependencies
│── .env                  # API keys (ignored in Git)
│── README.md             # Documentation
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Future Enhancements
- ✅ Support for multiple resume formats (DOCX, TXT)
- ✅ Improved AI suggestions for stronger resume optimization
- ✅ More detailed ATS scoring breakdown

---

## ✨ Contributors
Developed by **Shiza Khurram** 🚀

---

## ⭐ Acknowledgments
- **Google Gemini AI** for text processing
- **Streamlit** for UI development

---

## 📩 Contact
For inquiries, reach out via [https://github.com/shizakhurram].

Happy job hunting! 🎯

