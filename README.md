# RecruitRapid
Final Year Project Automated AI CV Screening Tool
# Automated CV Screening Tool

An AI-powered web application that automatically screens and ranks candidate CVs using Natural Language Processing (NLP) and Machine Learning (ML). 

## Project Aims

- Automate the CV screening process to reduce human bias and inefficiencies.
- Use AI and NLP to extract meaningful insights from CVs.
- Help recruiters make faster, fairer, and more informed hiring decisions.

## Features

- Upload PDF or DOCX CVs through a simple web interface.
- Automatically extract skills, qualifications, and experience.
- Score and rank candidates using ML algorithms.
- View results instantly on the webpage.
- Compliant with GDPR and ethical AI practices.

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Python, Flask
- **Machine Learning**: Random Forest, SVM
- **NLP**: spaCy, BERT
- **Libraries**: pandas, NumPy, scikit-learn
- **Deployment**: Localhost / GitHub Pages (static site)

## Model & Methodology

- **Preprocessing**: Tokenization, stop-word removal, NER.
- **Training**: Random Forest and SVM classifiers using a balanced CV dataset.
- **Bias Mitigation**: Algorithmic fairness audits, diverse datasets, and explainable AI.

## Project Structure

```
project-root/
│
├── static/
│   └── styles.css
├── templates/
│   └── index.html
│   └── upload.html
├── app.py
├── model.pkl
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/automated-cv-screening-tool.git
    cd automated-cv-screening-tool
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask app:
    ```bash
    python app.py
    ```

4. Open your browser and navigate to:
    ```
    http://localhost:5000
    ```

## Legal & Ethical Compliance

- Complies with **GDPR** for secure data handling.
- Avoids algorithmic bias through explainable AI techniques.
- Promotes inclusive hiring practices.


## Author

**Zishan Ahmed**  
