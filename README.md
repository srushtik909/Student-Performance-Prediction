# 🎓 Student Performance Prediction System

A machine learning-based web application that predicts student performance based on various factors and provides interactive visualizations for better insights.

## 🌟 Features

- **Real-time Performance Prediction**: Get instant predictions of student performance based on multiple factors
- **Interactive Dashboard**: Beautiful and responsive UI built with Streamlit
- **Data Visualization**: Multiple chart types to understand the data better:
  - Gauge Chart for Final Score Prediction
  - Pie Chart for Data Distribution
  - Line Chart comparing Past and Predicted Scores
  - Bar Chart for Factor Comparison
- **User-friendly Interface**: Easy-to-use input forms for student data
- **Responsive Design**: Works well on both desktop and mobile devices

## 📊 Input Parameters

The system considers the following factors for prediction:
- Study Time (hours)
- Number of Absences
- Past Scores (%)
- Number of Online Courses Completed
- Assignment Completion Rate (%)
- Time Spent on Social Media (hours/week)

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Student_Performance_Prediction.git
cd Student_Performance_Prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run finalapp.py
```

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Data Visualization**: Plotly
- **Machine Learning**: NumPy, Pandas
- **Data Processing**: Python

## 📈 Visualization Types

1. **Gauge Chart**
   - Shows predicted final score
   - Color-coded ranges for different performance levels

2. **Pie Chart**
   - Displays distribution of various factors
   - Interactive tooltips for detailed information

3. **Line Chart**
   - Compares past scores with predicted scores
   - Includes trend analysis

4. **Bar Chart**
   - Compares different input parameters
   - Color gradient for better visualization

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
