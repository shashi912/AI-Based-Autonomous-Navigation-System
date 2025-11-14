
# 🚗 AI-Based Autonomous Navigation System  
Predicting next-step steering commands using Machine Learning & Deep Learning


## 📌 Overview  
This project builds an **AI-driven navigation decision system** that predicts the future steering angle of a vehicle/robot based on sensor data (speed, heading, yaw rate, accelerations, obstacle distance, etc.).

It demonstrates **end-to-end Data Science + ML engineering**:

- Synthetic dataset generation  
- Data cleaning & EDA  
- Feature engineering  
- Random Forest Model  
- LSTM Sequence Model  
- Evaluation (RMSE, R²)  
- Visualizations  
- Model export (RF + LSTM)

This project is an excellent demonstration of **industry-level skills** for self-driving, robotics, automation, and IoT analytics.



## 🧠 Key Features  
- Synthetic realistic navigation dataset  
- Lags, rolling windows, temporal features  
- Random Forest baseline model  
- Deep LSTM time-series model  
- Metrics: RMSE, R²  
- Feature importance visualization  
- Actual vs Predicted steering plots  
- Fully modular code architecture  
- Saved model artifacts  



## 🛠 Tech Stack  
- **Python 3.10+**  
- **NumPy, Pandas** (data processing)  
- **Matplotlib, Seaborn** (visualization)  
- **Scikit-Learn** (Random Forest)  
- **TensorFlow / Keras** (LSTM)  
- **Joblib** (model saving)  
- **Jupyter Notebook / Colab**  



## 📦 Project Structure

ai-autonomous-navigation/
├── data/
│ └── synthetic_generation.ipynb
├── notebooks/
│ └── 01_data_exploration_and_modeling.ipynb
├── src/
│ ├── data_generation.py
│ ├── features.py
│ ├── train_rf.py
│ ├── train_lstm.py
├── artifacts/
│ └── saved models (RF + LSTM)
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore

## ** Project Setup
### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/ai-autonomous-navigation.git
cd ai-autonomous-navigation

2️⃣ Create virtual environment
python -m venv venv
source venv/bin/activate     # Windows: venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the notebook
jupyter notebook notebooks/01_data_exploration_and_modeling.ipynb

🚀 Future Enhancements

Integrate real driving datasets (CARLA, AirSim, ApolloSim)

Multi-step steering prediction

Add braking & throttle prediction

Deploy model as REST API / FASTAPI service

Build a ROS2 node for real robot navigation

Sensor fusion (Camera + Lidar + IMU)

Add anomaly detection (collision risk prediction)

👨‍💻 Author

Shashi Kumar Gugloth
AI & Data Science Enthusiast
India

📜 License

This project is licensed under the MIT License.
See the LICENSE file for full text.

🌐 Languages / Tools Used

Python

Markdown

Bash

Git / GitHub

