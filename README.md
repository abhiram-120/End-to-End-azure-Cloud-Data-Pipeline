# Real-Time Personalized Recommender System

This project builds an end-to-end, production-grade recommender system designed to serve real-time personalized recommendations for an e-commerce use case. It includes data pipelines, a machine learning model, an API, and a dashboard.

## Goals
- Real-time data ingestion
- Collaborative filtering with user/item embeddings
- FastAPI-based microservice
- Cloud deployment with Docker

architecture


🟦 User Events (clicks / purchases)
↓
🟩 Data Ingestion (Kafka or simulated Python queue)
↓
🟨 Data Storage (Postgres, CSV, or other database)
↓
🟥 ML Model (collaborative filtering, trained in PyTorch/TensorFlow)
↓
🟪 Recommendation API (FastAPI serving top-N recommendations)
↓
🟧 Dashboard (Streamlit showing user engagement, most popular products)
