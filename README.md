# ForestFlow - An End-to-End ML Pipeline with DVC and MLflow

ForestFlow is a robust end-to-end machine learning pipeline that integrates **DVC (Data Version Control)** and **MLflow** to streamline data management, experiment tracking, and model deployment. This project automates the ML lifecycle, ensuring reproducibility and efficient model development.

## 🚀 Feature

- **Data Versioning**: Utilizes DVC to manage datasets efficiently.
- **Experiment Tracking**: Uses MLflow to log and compare model performance.
- **Pipeline Automation**: Automates preprocessing, training, and evaluation steps.
- **Reproducibility**: Ensures consistency in ML experiments across different environments.
- **Model Deployment**: Saves and tracks the best-performing models for production use.

## 🛠️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/krishshah9944/ForestFlow-An-End-to-End-ML-Pipeline-with-DVC-and-MLflow.git
cd ForestFlow-An-End-to-End-ML-Pipeline-with-DVC-and-MLflow
```

### 2️⃣ Create a Virtual Environment
#### For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```
#### For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up DVC
```bash
dvc init
dvc pull  # Fetch the dataset and artifacts if available
```

### 5️⃣ Run the ML Pipeline
```bash
python pipeline.py
```

## 📌 Usage

1. **Run Data Preprocessing**: Cleans and prepares raw data for training.
2. **Train ML Models**: Trains various models and logs results in MLflow.
3. **Track Experiments**: Compare multiple runs using MLflow UI.
4. **Deploy the Best Model**: Stores the best model for inference.

## 🤝 Contributing

Feel free to contribute by submitting issues or pull requests. Suggestions and improvements are always welcome!

## 📧 Contact

For inquiries, reach out via LinkedIn or email:

- **LinkedIn**: [Krish Shah](https://www.linkedin.com/in/krishshah9944/)
- **Email**: krishshah9944@gmail.com



