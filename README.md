# 🏏✨ IPL Win Predictor

Welcome to the **IPL Win Predictor**!  
This project leverages the power of **machine learning** to predict the winning probability of IPL teams in real time, blending the excitement of cricket with cutting-edge data science. Whether you're a cricket fan, a data enthusiast, or just exploring, this project offers a fun and insightful way to see sports analytics in action!

---

<p align="center">
  <img src="[screenshot.png](https://github.com/user-attachments/assets/aa300501-f30d-4e60-b30b-38f66a204df2)" alt="App Screenshot" width="80%" style="border-radius: 8px; box-shadow: 0 4px 24px #00000033;">
</p>

---

## 🚀 Features

- 🎯 **Live Win Probability:** Dynamic, real-time predictions as the match unfolds
- 🖥️ **Intuitive Dashboard:** Clean and interactive user interface for entering match scenarios
- 📊 **Beautiful Visualizations:** Engaging charts and stats for deeper insights
- ⚡ **ML Powered:** Built with Python, scikit-learn, pandas, and Streamlit
- 🛠️ **Customizable:** Easily extensible for other cricket leagues or sports

---

## 💡 How It Works

1. **Data Collection:** Scrapes and processes historical IPL data
2. **Feature Engineering:** Extracts essential match features (runs, wickets, overs, etc.)
3. **Model Training:** Trains machine learning models (Logistic Regression, Random Forest, etc.)
4. **Prediction:** User enters match state, and the model returns instant win probabilities

---

## 📦 Project Structure

```text
IPL-win-predictor/
├── data/           # Raw & processed datasets
├── models/         # Trained ML models
├── notebooks/      # Jupyter notebooks for EDA & training
├── app/            # Web/GUI application code (Streamlit)
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/pra48-cyber/IPL-win-predictor.git
cd IPL-win-predictor

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## 🏃‍♂️ Quick Start

1. **Launch the Web App:**
   ```bash
   cd app
   streamlit run app.py
   ```
2. Open the provided local URL in your browser.
3. Enter match details (teams, score, wickets, overs, etc.) and instantly view win predictions!

---

## 🏏 Example Use Case

> **Team A:** 150/4 in 16 overs  
> **Team B:** Chasing 180  
>
> **Prediction:** Team A has a **65%** chance of winning!

---

## 🤖 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/> 
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white"/>
</p>

---

## 🙌 Contributions

All contributions are welcome!  
Feel free to open issues or submit pull requests for features, bug fixes, or enhancements.

---

## 📬 Contact

- **Author:** [pra48-cyber](https://github.com/pra48-cyber)
- **Email:** prasadmhaske48@gmail.com

---

<p align="center"><em>“Cricket is not just a game, it’s a way of life.”<br>– Predict smarter, play smarter!</em></p>
