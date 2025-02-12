# Resume Screening Model 📝🔍

This project is a **Resume Screening Application** powered by **Machine Learning** and built using **Streamlit**. It allows users to upload resumes in **PDF, DOCX, or TXT formats** and predicts the job category based on the extracted text.

## 🔥 Features
- **Automated Resume Classification**: Uses an **SVM classifier** with **TF-IDF vectorization** to categorize resumes.
- **Multi-format Support**: Extracts text from **PDF, DOCX, and TXT** files.
- **Text Cleaning & Processing**: Prepares resume text by removing noise and special characters.
- **User-friendly UI**: Built with **Streamlit** for easy interaction.
- **Fast & Accurate Predictions**: Pre-trained model ensures quick and reliable results.

## 🚀 Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/resume-screening-model.git
cd resume-screening-model
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Streamlit App
``` bash
streamlit run app.py
```
### 🛠️ Technologies Used
Python
Streamlit
Scikit-learn
TF-IDF Vectorization
SVM Classifier
PyPDF2 & python-docx (for text extraction)
### 🎯 Use Cases
HR & Recruitment: Automate resume screening and categorization.
Job Portals: Improve job-matching efficiency.
Career Guidance: Help individuals understand their career fit.
### 📌 Future Improvements
Improve classification accuracy with deep learning models.
Support more resume formats (e.g., HTML).
Enhance UI with interactive visualizations.
