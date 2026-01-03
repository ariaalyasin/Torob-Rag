# MLOps Project - Phase 1: Product Retrieval RAG System

## Project Overview
Building an intelligent shopping assistant that retrieves relevant products from Torob's e-commerce database based on user queries (text and/or images).

## Dataset
- **Source**: Torob E-commerce Platform
- **Format**: Parquet files (9 tables)
- **Size**: ~1M records

### Tables:
- `base_products.parquet` - Base product information
- `members.parquet` - Shop-specific product listings
- `searches.parquet` - User search logs
- `base_views.parquet` - Product view logs
- `final_clicks.parquet` - Click logs
- `shops.parquet` - Shop information
- `categories.parquet` - Product categories
- `brands.parquet` - Brand information
- `cities.parquet` - City information

## Project Structure
```
mlops/
├── Data/                   # Dataset files
├── notebooks/              # Jupyter notebooks for exploration
├── src/                    # Source code
├── configs/                # Configuration files (YAML)
├── outputs/                # Model outputs, embeddings
├── reports/                # EDA reports, visualizations
├── requirements.txt        # Python dependencies
└── README.md              # This file
```

## Phase 1 Tasks
1. ✅ Dataset setup
2. 🔄 Exploratory Data Analysis (EDA)
3. ⏳ Data Cleaning & Preprocessing
4. ⏳ Feature Engineering (Text & Image Embeddings)
5. ⏳ Model Development:
   - Text-only RAG
   - Image-only RAG
   - Multimodal RAG (Bonus)
6. ⏳ Hyperparameter Tuning
7. ⏳ Evaluation

## Setup
```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Deadline
December 30, 2025 (دی 9, 1404)
