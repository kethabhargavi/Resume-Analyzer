# 🧠 Resume Analyzer

A smart, AI-powered web application that evaluates resumes against job descriptions to provide actionable insights, improve alignment, and boost hiring success.

---

## 🚀 Overview

**Resume Analyzer** helps job seekers understand how well their resume matches a specific job role. By leveraging NLP techniques and intelligent scoring, the system highlights strengths, identifies gaps, and suggests improvements—making your application more competitive.

---

## ✨ Key Features

* 📄 **Resume Upload & Parsing**
  Upload resumes in supported formats and extract structured data.

* 🔍 **Job Description Matching**
  Compare resumes with job descriptions to evaluate relevance.

* 🧠 **Skill & Keyword Extraction**
  Identify important skills and keywords using NLP techniques.

* 📊 **Match Score Calculation**
  Generate a similarity score using hybrid ranking methods.

* ⚠️ **Missing Skills Detection**
  Highlight critical skills absent in the resume.

* 💡 **Improvement Insights**
  Provide suggestions to enhance resume quality.

* 📱 **Responsive UI**
  Clean and user-friendly interface for seamless interaction.

---

## 🛠️ Tech Stack

| Layer    | Technology                                                |
| -------- | --------------------------------------------------------- |
| Frontend | React.js, JavaScript                                      |
| Backend  | Python, Flask                                             |
| Styling  | CSS                                                       |
| NLP      | Resume parsing, keyword extraction, similarity algorithms |

---

## 🧩 How It Works

The system evaluates resumes using a hybrid scoring approach:

```
Final Score =
0.7 × Semantic Similarity (Sentence Transformers)
+
0.3 × Keyword Matching (BM25)
```

* **Semantic Similarity** → Understands contextual meaning
* **Keyword Matching** → Ensures ATS-friendly optimization

---

## 📌 Use Case

* Students preparing for placements
* Job seekers optimizing resumes
* Recruiters screening candidates efficiently

---
## 📂 Project Setup

Follow these steps to run the project locally:

### 🔧 Prerequisites

Make sure you have the following installed:

* **Node.js** (v14 or higher)
* **npm** or **Yarn**
* **Python** (v3.7 or higher)
* **Git**

---

### ⚙️ Installation Steps

```bash
# Clone the repository
git clone https://github.com/kethabhargavi/Resume-Analyzer.git

# Navigate to the project folder
cd Resume-Analyzer
```

### ▶️ Run Frontend

```bash
# Install frontend dependencies
npm install

# Start React application
npm start
```

Frontend will run at: `http://localhost:3000`

---

### ▶️ Run Backend (Flask)

```bash
# Navigate to backend folder (if separate)
cd backend

# Install Python dependencies
pip install -r requirements.txt

# Run Flask server
python app.py
```

Backend will run at: `http://localhost:5000`

---

### 🔗 Connecting Frontend & Backend

* Ensure API endpoints in React match the Flask server URL
* Example:

```javascript
const API_URL = "http://localhost:5000";
```

---

### 🧪 Testing the Application

1. Upload a resume
2. Paste a job description
3. Click **Analyze**
4. View match score and insights

---

If your backend folder structure is different, tell me—I’ll customize this exactly to your repo so recruiters won’t find any confusion.

---

## 📈 Future Enhancements

* 🤖 AI-powered resume suggestions
* 📑 PDF report generation
* 📊 Advanced ATS scoring system
* 📂 Support for multiple resume formats (DOCX, PDF, TXT)
* 🌐 Deployment with cloud integration

---

## 🖼️ Demo (Optional)

**Output Screenshots**
<img src="images/Screenshot 2026-04-02 105232.png" width="450">

---

## 👩‍💻 Author

**Bhargavi Ketha**
📌 Passionate about AI, NLP, and building impactful solutions for real-world problems.

---

## ⭐ Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 💡 Final Note

This project is not just a tool—it’s a **career companion** that helps bridge the gap between your skills and your dream job.



