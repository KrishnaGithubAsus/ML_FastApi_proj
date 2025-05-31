# To run the project, run the following command in project terminal

concurrently "uvicorn app_api:app --reload" "streamlit run FrontApp.py"

# ==========================   PROJECT DESCRIPTION    ============================

# Insurance Purchase Prediction Application

An end-to-end machine learning project that predicts insurance premium rate ["high", "medium" ,"low"] using a RandomForest model, wrapped in a REST API backend with **FastAPI**, and a user-friendly **Streamlit** frontend.

The model is trained on TOY-dataset.
---

## 🚀 Features

- **Robust ML Model** trained on insurance dataset using `scikit-learn`
- **REST API Backend** powered by FastAPI serving real-time predictions
- **Interactive Frontend** built with Streamlit for intuitive user input
- **Seamless Development Setup** with virtual environment and dependency management
- **Single-command startup** option using `concurrently` for streamlined development workflow.
