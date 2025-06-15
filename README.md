# Amazon-Product-Review-Intelligence-System
This project showcases an end-to-end machine learning pipeline that transforms unstructured Amazon product reviews into real-time actionable insights using AWS services and NLP techniques.


🚀 Key Features:
📥 Data Ingestion & ETL: Automated pipeline using AWS Glue to clean, transform, and prepare large-scale Amazon review data.

💬 Sentiment Classification: Trained a custom XGBoost classifier on processed review text to classify customer sentiment (positive, neutral, negative).

🧠 Text Summarization: Deployed Hugging Face T5 model via AWS Lambda to generate concise summaries of lengthy customer feedback.

🧪 Model Deployment: Hosted model inference via SageMaker endpoints, orchestrated with AWS Step Functions and Lambda.

📊 Interactive Dashboard: Built a user-friendly Streamlit dashboard for real-time sentiment insights, keyword clouds, and customer pain points.

🔔 Monitoring & Alerting: Integrated CloudWatch and SNS for health checks, error alerts, and performance tracking of deployed services.

🛠️ Tech Stack:
Language: Python (Pandas, Scikit-learn, XGBoost, Transformers)

AWS: S3, Glue, Lambda, SageMaker, Step Functions, CloudWatch, SNS

Visualization: Streamlit / Power BI (optional)

Deployment: Docker (optional), REST APIs

📎 Use Cases:
Customer support analytics

Real-time feedback monitoring

Scalable ML systems on cloud

NLP in eCommerce
