#  Hybrid Anime Recommender System with Comet.ml, DVC, Jenkins & Kubernetes

[![Comet.ml](https://img.shields.io/badge/Comet.ml-Experiment%20Tracking-orange)](https://www.comet.ml/)
[![DVC](https://img.shields.io/badge/DVC-Data%20Versioning-blue)](https://dvc.org/)
[![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-red?logo=jenkins)](https://jenkins.io/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-1.25%2B-blue?logo=kubernetes)](https://kubernetes.io/)

Advanced hybrid recommendation system for anime titles, combining collaborative filtering and content-based approaches. Features full MLOps integration with experiment tracking, data versioning, CI/CD automation, and Kubernetes deployment.

##  Project Overview
Generates personalized anime recommendations using:
- **Collaborative Filtering**: Matrix factorization for user-item interactions
- **Content-Based Filtering**: Genre/tag-based similarity using TF-IDF
- **Hybrid Approach**: Weighted combination of both methods


##  Key Features
- **Hybrid Recommendation Engine**:
  - Collaborative filtering with implicit feedback
  - Content-based filtering using anime metadata
  - Dynamic blending of recommendation scores
- **MLOps Infrastructure**:
  - Comet.ml for experiment tracking and visualization
  - DVC for dataset versioning and pipeline management
  - Jenkins for CI/CD automation
  - Kubernetes for container orchestration
- **Scalable Deployment**:
  - Microservices architecture
  - Horizontal pod autoscaling
  - GPU-accelerated inference
- **Evaluation Framework**:
  - Precision@K, Recall@K, NDCG metrics
  - A/B testing capabilities
  - Recommendation diversity analysis

##  Getting Started

### Prerequisites
- Python 3.9+
- Docker 20.10+
- Kubernetes cluster (Minikube or cloud-based)
- Comet.ml account
- Jenkins server

### Installation
```bash
# Clone repository
git clone https://github.com/zakkou/Hybrid-Anime-Recommender-System-with-Comet-ML-DVC-Jenkins-and-Kubernetes.git
cd Hybrid-Anime-Recommender-System-with-Comet-ML-DVC-Jenkins-and-Kubernetes

# Install dependencies
pip install -r requirements.txt

# Setup environment variables
export COMET_API_KEY="your_comet_api_key"
export DVC_REMOTE_URL="gs://your-bucket/dvc-storage"  # For GCP
