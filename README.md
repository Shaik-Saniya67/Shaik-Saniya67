<h1 align="center">Saniya Shaik</h1>
<h3 align="center">AI/ML & Data Science | Python Developer</h3>

<p align="center">
  Final-year B.Tech CSE student building ML systems that are validated honestly and shipped as working apps.<br/>
  <b>Open to fresher roles and internships in AI/ML and Data Science.</b>
</p>

<p align="center">
  <a href="https://shaik-saniya67.github.io/Portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-View-181717?style=for-the-badge&logo=githubpages&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/shaiksaniya67">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:saniyashaik.in@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About

I build end-to-end ML applications: real data, honest evaluation, and a deployed interface on top. My work focuses on model validation (held-out testing, leakage checks, calibration) and on LLM-powered tools that stay grounded in their source documents.

---

## Featured Projects

### [Sylvan Watch: Satellite Forest-Loss Detection](https://github.com/Shaik-Saniya67/Sylvan-Watch) · [Live app](https://project-mzb0n.vercel.app/)
Compares Sentinel-2 imagery from two years to flag where forest canopy disappeared, and returns georeferenced loss polygons with area in hectares and model confidence. Built for Green Shift Hacks 2026.
- Trained on 174 real tiles from 5 sites in Brazil, Indonesia and India, pulled through Google Earth Engine
- Compared a spectral baseline, Random Forest and Siamese U-Net on **geographically held-out sites**; Random Forest scored F1 0.545 (95% CI 0.487–0.598), against 0.392 for the baseline
- Reports calibration, per-site scores and limitations openly
- **Stack:** Python, scikit-learn, PyTorch, FastAPI, Next.js, Google Earth Engine, GitHub Actions, Vercel, Render

### [MLProof: ML Evaluation Integrity Auditor](https://github.com/Shaik-Saniya67/MLProof_HackSphere) · [Live demo](https://mlproof-hackshphere-2k26.streamlit.app/)
Checks whether a model's reported performance is supported by its evidence. A "96% accuracy" claim can hide a model that ignores the minority class.
- Flags class imbalance, potential leakage, train/test contamination and overfitting with severity-rated findings
- Guided no-code workflow that compares Logistic Regression, Random Forest, XGBoost and CatBoost on one shared split, with PDF/JSON reports
- **Stack:** Python, Streamlit, scikit-learn, XGBoost, CatBoost, Plotly

### [NammaSeve: Kannada Public-Notice Explainer](https://github.com/Shaik-Saniya67/NammaSeve)
Explains Kannada government notices in simple Kannada, Telugu, Hindi or English, and answers questions using only the uploaded notice, citing the exact supporting sentence.
- Reads text PDFs directly and falls back to Kannada + English OCR for scans and photos
- Refuses to answer when the notice doesn't say, and offers read-aloud audio
- **Stack:** Python, Streamlit, Groq (Llama 3.3 70B), PyMuPDF, Tesseract OCR, gTTS

### [EvidenceTap: Tamper-Evident Evidence Capture](https://github.com/Shaik-Saniya67/EvidenceTap) · [Live demo](https://evidencetap.onrender.com/)
One tap records audio, time and location into a record that shows if anything is changed afterwards. Built for HerHack 2026 (Women Safety).
- SHA-256 hash chain, chunked uploads with retry and recovery, and a public verify page that hashes files in the browser
- 74 automated checks run in GitHub Actions
- **Stack:** Python, FastAPI, SQLite, JavaScript

**Also built:** [DataMind AI](https://github.com/Shaik-Saniya67/Datamind-ai) (chat with your CSV using Groq and SQL) · [Meeting-to-Action Agent](https://github.com/Shaik-Saniya67/meeting-to-action-agent) (Gemini-powered meeting analysis)

---

## Education

**B.Tech, Computer Science & Engineering** — SITAMS, Chittoor, Andhra Pradesh
Final year | CGPA: 8.54 / 10

---

## Experience

**Internships:** Strydo Technologies · Infosys Springboard · CodSoft · Forge

---

## Certifications

- Kaggle: Generative AI Intensive
- Kaggle: Python Programming

---

## Technical Skills

**Languages & Databases**<br/>
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Data Science & ML**<br/>
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

**Apps & APIs**<br/>
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**Cloud & Tools**<br/>
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Currently exploring:** LLM APIs (Groq, Gemini), agentic patterns, geospatial ML

---

<p align="center"><i>Open to opportunities. Let's connect.</i></p>
