# 🌍 AeroNexus – Spatial AI Air Quality Intelligence Platform

### Transforming Air Quality Data into Intelligent Environmental Insights

AeroNexus is an AI-powered air quality monitoring and prediction platform designed to analyze environmental data, predict Air Quality Index (AQI), detect unusual pollution patterns, and visualize air quality insights through an interactive spatial dashboard.

The platform combines Machine Learning, real-time environmental data integration, and modern data visualization to make air quality information easier to understand and monitor.

---

## 🚀 Key Features

### 🌐 Spatial AI Dashboard
- Interactive dashboard with a modern spatial interface.
- 3D Earth visualization for an immersive environmental monitoring experience.
- Dark glassmorphism UI with a futuristic design.
- Visual representation of environmental insights.

### 📊 Air Quality Analysis
- Analyze air pollution and environmental parameters.
- Explore air quality trends through interactive visualizations.
- Understand pollution patterns using historical data.

### 🤖 AI-Powered AQI Prediction
- Machine Learning-based AQI prediction.
- Random Forest model for predictive analysis.
- Data-driven insights to understand potential air quality conditions.

### 🔍 Anomaly Detection
- Isolation Forest-based anomaly detection.
- Identify unusual environmental patterns.
- Support the identification of abnormal pollution observations.

### 🌤️ Live Environmental Data
- Integration with the Open-Meteo API.
- Retrieve live environmental information.
- Combine external environmental data with analytical insights.

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Frontend / Dashboard | Streamlit |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Data Visualization | Plotly, Matplotlib |
| Model Serialization | Joblib |
| External API | Open-Meteo API |
| Development Environment | VS Code, Jupyter Notebook |
| Version Control | Git, GitHub |

---

## 🧠 Machine Learning Models

AeroNexus incorporates machine learning techniques for environmental intelligence:

**1. Random Forest**
- Used for AQI prediction.
- Learns patterns from environmental data.
- Supports data-driven air quality analysis.

**2. Isolation Forest**
- Used for anomaly detection.
- Identifies unusual patterns in environmental observations.
- Helps highlight potentially abnormal pollution conditions.

---

## 📂 Project Structure

```text
AeroNEXUS/
│
├── app.py
│
├── models/
│   ├── airguard_anomaly_detector.joblib
│   ├── airguard_best_model.joblib
│   ├── model_comparison.csv
│   └── model_metrics.json
│
├── data/
│
├── notebooks/
│
├── docs/
│
├── assets/
│
├── requirements.txt
├── README.md
└── .gitignore
```

*Note: The structure above represents the intended organization. Adjust folder and file names to match your actual repository.*

---

## ⚙️ Installation and Setup

### Prerequisites
- Python 3.12 recommended.
- Git.
- pip package manager.

### 1. Clone the Repository

```bash
git clone https://github.com/PriyaDash10/AeroNexus.git
```

### 2. Navigate to the Project Directory

```bash
cd AeroNexus
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Environment

**Windows:**

```bash
.venv\Scripts\activate
```

**Linux / macOS:**

```bash
source .venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

## 📈 Project Objectives

- Make air quality information more accessible and understandable.
- Apply Machine Learning to environmental data analysis.
- Predict AQI using trained machine learning models.
- Detect unusual pollution patterns through anomaly detection.
- Integrate live environmental information.
- Present environmental insights through interactive spatial visualizations.

---

## 🔮 Future Enhancements

- Real-time pollution monitoring across multiple geographical locations.
- Advanced geospatial air quality visualization.
- Improved predictive models using additional environmental parameters.
- Interactive pollution hotspot identification.
- Location-based air quality alerts and notifications.
- Integration with additional environmental data sources.

---

## 👩‍💻 Developer

**Priyadarshani Dash**

MCA Student | AI & Machine Learning Enthusiast | Software Developer

GitHub: [@PriyaDash10](https://github.com/PriyaDash10)

---

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐ on GitHub.

**AeroNexus – Making Environmental Intelligence Smarter, More Accessible, and More Visual.**
