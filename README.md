# End-to-End AI/ML Projects

A curated collection of end-to-end Artificial Intelligence and Machine Learning projects demonstrating the complete lifecycle from data preparation and model training to production deployment on cloud platforms.

---

## Projects

### Production GCP Deployments

#### Brain Tumor Image Classification — GCP
A production-grade 4-class brain tumor MRI classification system deployed on Google Cloud Platform.

- **Model:** VGG16 (Transfer Learning) — 94.44% test accuracy
- **Classes:** Glioma, Meningioma, No Tumor, Pituitary
- **Backend:** FastAPI + Docker + Cloud Run
- **Frontend:** Next.js + Tailwind CSS + Cloud Run
- **MLOps:** Vertex AI Model Registry + Cloud Build CI/CD
- **Training:** Two-phase fine-tuning on Kaggle Tesla T4 GPU
- **Repository:** https://github.com/prem332/brain-tumor-image-classification

> The live deployment URL may be temporarily suspended to avoid ongoing GCP billing charges. The project is fully functional and can be redeployed within 15–20 minutes using the CI/CD pipeline. Production screenshots are available in the repository as proof of the working deployment.

---

#### Mental Health Sentiment Analysis — GCP
A production-grade mental health sentiment classification system deployed on Google Cloud Platform.

- **Repository:** https://github.com/prem332/mental-health-sentiment-gcp

> The live deployment URL may be temporarily suspended to avoid ongoing GCP billing charges.

---

### Classical ML Projects

| Project | Type | Tech Stack |
|---|---|---|
| Brain Tumor Detection | Image Classification | VGG16, TensorFlow, Flask |
| Mental Health Sentiment Analysis | NLP Classification | BiLSTM, TensorFlow, Flask |
| House Price Prediction | Regression | Scikit-learn, Flask |
| Loan Approval Prediction | Classification | Scikit-learn, Flask |

---

## Repository Structure

```
End_to_End_AI_ML_projects/
├── Brain_Tumor_Image_Classification_GCP/    # Submodule → GCP production deployment
├── Mental_Health_Sentiment_Analysis_GCP/    # Submodule → GCP production deployment
├── Brain_Tumor_Detection_Image_classificaion/  # Classical ML project (original)
├── House_Price_Prediction_System/           # Classical ML project
├── loan_approval_prediction/                # Classical ML project
└── README.md
```

---

## Tech Stack Across Projects

### Machine Learning
- TensorFlow, Keras, Scikit-learn
- VGG16, BiLSTM, Random Forest, XGBoost
- Transfer Learning, Two-phase Fine-tuning

### MLOps and Cloud
- Google Cloud Platform (Cloud Run, Cloud Build, GCS, Vertex AI)
- Docker, Artifact Registry
- GitHub Actions CI/CD
- Vertex AI Model Registry

### Backend and Frontend
- FastAPI, Flask
- Next.js, React, TypeScript
- Tailwind CSS, HTML, CSS

---

## Note on Live Deployments

GCP-deployed projects may be temporarily suspended to avoid ongoing cloud billing charges. All projects are fully functional and can be redeployed within 15–20 minutes using the CI/CD pipelines documented in their respective repositories. Production screenshots are available in each project repository as proof of working deployments.

---

## Author

Prem Kumar — AI/ML Engineer  
GitHub: https://github.com/prem332
