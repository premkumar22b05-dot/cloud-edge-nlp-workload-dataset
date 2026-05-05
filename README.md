Cloud-Edge NLP Workload Dataset

Overview
This dataset contains synthetically generated textual workload samples designed for NLP-based cloud-edge resource allocation research.

It supports:
- Semantic workload classification
- Latency-aware scheduling
- Privacy-aware task allocation


 Dataset Details

- Total Samples: 50,000 (full dataset used in paper)
- This repository contains a representative subset for reproducibility

Data Sources (Simulated)
- Application Logs
- User Service Requests
- System Alerts
- Application Notifications

 Labels

Each sample includes:

- priority: Low / Medium / High  
- latency: Low / High  
- compute: Low / Medium / High  
- privacy: Public / Sensitive  

 Files

- `train.csv` → Training dataset  
- `validation.csv` → Validation dataset  
- `test.csv` → Testing dataset  

 Use Case

This dataset is designed for:
- NLP classification using Transformer models (RoBERTa, DistilBERT)
- Cloud-edge workload orchestration research
- Intelligent resource allocation systems

 Note

The dataset is synthetically generated based on patterns observed in real-world systems such as:
- System logs
- User queries
- Monitoring alerts

It does NOT contain real user data.

 Related Paper

Adaptive NLP-Driven Cloud–Edge Framework for Latency-Critical and Secure Applications

 Dataset Availability

This dataset is publicly available for research purposes.



## 📜 License

MIT License
