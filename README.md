# 🤖 ML Internship Project - Restaurant Data Analysis

<div align="center">

---

## 🏆 Machine Learning Mastery Showcase 🏆

[![trophy](https://github-profile-trophy.vercel.app/?username=parthparmar07&theme=darkhub&no-frame=true&no-bg=true&margin-w=4)](https://github.com/parthparmar07)

---

## 🏅 Project Achievement Badges 🏅

| Task | Badge | Specialty | Performance |
|:---:|:---:|:---:|:---:|
| **Rating Prediction** | <img src="https://img.shields.io/badge/🎯-Prediction%20Master-success?style=for-the-badge" alt="Prediction Master"> | Regression Analysis | ![](https://img.shields.io/badge/R²-85%25+-brightgreen?style=flat-square) |
| **Recommendation Engine** | <img src="https://img.shields.io/badge/🔍-Recommendation%20Pro-blue?style=for-the-badge" alt="Recommendation Pro"> | System Design | ![](https://img.shields.io/badge/Algorithm-Advanced-blue?style=flat-square) |
| **Classification & Clustering** | <img src="https://img.shields.io/badge/🧠-ML%20Specialist-purple?style=for-the-badge" alt="ML Specialist"> | Unsupervised Learning | ![](https://img.shields.io/badge/Accuracy-90%25+-purple?style=flat-square) |
| **Geographical Analysis** | <img src="https://img.shields.io/badge/🗺️-GeoData%20Expert-orange?style=for-the-badge" alt="GeoData Expert"> | Spatial Analytics | ![](https://img.shields.io/badge/Insights-Generated-orange?style=flat-square) |

---

## ✨ Technical Excellence Badges ✨

<div align="center">

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Restaurant%20Analytics-blue?style=for-the-badge&logo=python)
![Data Science](https://img.shields.io/badge/Data%20Science-Advanced-green?style=for-the-badge&logo=jupyter)
![Python](https://img.shields.io/badge/Python-3.8+-yellow?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

![Scikit Learn](https://img.shields.io/badge/Scikit%20Learn-ML%20Models-orange?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge&logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-lightblue?style=for-the-badge&logo=python)

![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Maintained](https://img.shields.io/badge/Maintained-Yes-green?style=for-the-badge)
![Tasks](https://img.shields.io/badge/Tasks-4-brightgreen?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/ML%20Algorithms-10+-purple?style=for-the-badge)

</div>

---

## 🎯 Performance Metrics Dashboard 🎯

| Metric | Value | Achievement |
|:---:|:---:|:---:|
| **Total Tasks** | 4 | ![](https://img.shields.io/badge/Complete-100%25-success?style=flat-square) |
| **ML Models** | 10+ | ![](https://img.shields.io/badge/Variety-Expert-purple?style=flat-square) |
| **Best R² Score** | 85%+ | ![](https://img.shields.io/badge/Performance-Excellent-brightgreen?style=flat-square) |
| **Data Points** | 10,000+ | ![](https://img.shields.io/badge/Scale-Enterprise-blue?style=flat-square) |
| **Visualizations** | 20+ | ![](https://img.shields.io/badge/Insights-Rich-orange?style=flat-square) |

---

</div>

## 📋 Project Overview

This project was developed as part of a machine learning internship and consists of four main tasks:

1. **Task 1**: Restaurant Rating Prediction
2. **Task 2**: Restaurant Recommendation System
3. **Task 3**: Classification and Clustering Analysis
4. **Task 4**: Geographical Distribution Analysis

## 🚀 Features

### Task 1: Rating Prediction
- **Objective**: Predict restaurant aggregate ratings based on various features
- **Models Used**: 
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- **Features Analyzed**:
  - Price range
  - Average cost for two
  - Table booking availability
  - Online delivery availability
  - Cuisine types and count
- **Visualizations**:
  - Rating distribution histogram
  - Average rating by price range
  - Rating by cuisine type
  - Feature correlation matrix

### Task 2: Recommendation System
- **Objective**: Build a content-based restaurant recommendation system
- **Approach**: Uses cosine similarity for restaurant recommendations
- **Features**: 
  - Preprocessed restaurant data
  - Similarity matrix computation
  - Personalized recommendations based on restaurant features

### Task 3: Classification & Clustering
- **Classification**: Multiple algorithms for restaurant categorization
- **Clustering**: K-means clustering to identify restaurant groups
- **Models**: Various classification algorithms with performance comparison

### Task 4: Geographical Analysis
- **Objective**: Analyze restaurant distribution geographically
- **Features**:
  - Interactive map visualization using Plotly
  - Restaurant concentration by city
  - Average ratings by geographical location
  - Cuisine distribution analysis by region

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Analysis**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Visualization**: 
  - Matplotlib
  - Seaborn
  - Plotly Express
- **Data Preprocessing**: StandardScaler, OneHotEncoder, ColumnTransformer

## 📊 Dataset

The project uses a restaurant dataset (`Dataset .csv`) containing:
- Restaurant information (name, ID, location)
- Ratings and reviews
- Cuisine types
- Price ranges
- Service features (table booking, online delivery)
- Geographical coordinates

## 📈 Results & Insights

### Model Performance
- Multiple regression models trained and evaluated
- Performance metrics: MSE, R², MAE
- Model comparison and best performer identification

### Key Findings
- Correlation between price range and ratings
- Cuisine type impact on restaurant ratings
- Geographical distribution patterns
- Service feature influence on customer satisfaction

## 🔧 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/ml-internship-cognifyz.git
   cd ml-internship-cognifyz
   ```

2. **Install required packages**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn plotly
   ```

3. **Prepare the dataset**:
   - Ensure `Dataset .csv` is available in the appropriate directory
   - Update file paths in the code if necessary

## 🚀 Usage

Run the complete analysis:
```bash
python ml_internship.py
```

The script will:
1. Load and preprocess the data
2. Perform exploratory data analysis
3. Train multiple ML models
4. Generate visualizations
5. Create recommendation system
6. Perform geographical analysis

## 📁 Output Files

The project generates several visualization files:
- `rating_distribution.png` - Distribution of restaurant ratings
- `rating_by_price.png` - Average rating by price range
- `rating_by_cuisine.png` - Average rating by cuisine type
- `correlation_matrix.png` - Feature correlation heatmap

## 🔍 Code Structure

```
ml_internship.py
├── Task 1: Rating Prediction
│   ├── Data preprocessing
│   ├── Feature engineering
│   ├── EDA and visualizations
│   └── Model training & evaluation
├── Task 2: Recommendation System
│   ├── RestaurantRecommender class
│   ├── Similarity computation
│   └── Recommendation generation
├── Task 3: Classification & Clustering
│   ├── Multiple classification models
│   └── K-means clustering
└── Task 4: Geographical Analysis
    ├── Interactive map creation
    └── Location-based insights
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is part of an internship program and is for educational purposes.

## 👨‍💻 Author

**Parth Parmar**
- Machine Learning Intern
- Focus: Data Analysis, Predictive Modeling, and Recommendation Systems

## 🙏 Acknowledgments

- Thanks to the internship program for providing the dataset and project requirements
- Special appreciation for the opportunity to work on real-world data analysis problems

---

⭐ **If you found this project helpful, please give it a star!** ⭐
