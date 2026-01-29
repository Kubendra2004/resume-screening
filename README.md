# Resume Screening App 📄

An AI-powered Resume Screening and Ranking System built with **Streamlit**. It assists HR professionals by automating the resume screening process using Natural Language Processing (NLP).

## 🚀 Live Demo
**[Click here to view the live app on GitHub Pages](https://kubendra2004.github.io/resume-screening/)**

> **Note**: The live demo runs entirely in your browser using **stlite**. The first load may take a few seconds to initialize the Python environment.

## ✨ Features
-   **Upload Multiple Resumes**: Supports PDF and DOCX formats.
-   **Automated Ranking**: Uses TF-IDF and Cosine Similarity to rank resumes against a job description.
-   **Interactive Visualizations**: View ranking scores with Plotly charts.
-   **Export Results**: Download rankings as CSV or Text files.
-   **Privacy Focused**: When running via the live demo, all processing happens locally in your browser. No data is sent to a server.

## 🛠️ Installation & Local Run

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Kubendra2004/resume-screening.git
    cd resume-screening
    ```

2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the application**:
    ```bash
    streamlit run resume.py
    ```

## 📦 Tech Stack
-   **Frontend/UI**: Streamlit
-   **Deployment**: GitHub Pages (via stlite)
-   **NLP Parsing**: PyPDF2, python-docx, docx2txt
-   **Analysis**: scikit-learn (TF-IDF, Cosine Similarity), pandas
-   **Visualization**: Plotly

## 🤝 Contributing
Feel free to open issues or submit pull requests for improvements!
