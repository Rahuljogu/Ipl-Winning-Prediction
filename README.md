# IPL Win Probability Predictor 🏏

This project predicts the winning probability of an IPL (Indian Premier League) team during a live match, 
based on match conditions such as score, overs, wickets, and required run rate.  

It uses **machine learning** techniques to calculate real-time probabilities and assist in match analysis.

---

## 📂 Project Structure
```
ipl-win-probability/
  ├── IPL_Win_Prob.ipynb    # Jupyter Notebook with code & analysis
  ├── requirements.txt      # Python dependencies
  ├── .gitignore            # Ignore cache & checkpoint files
  └── README.md             # Project documentation
```

---

## ⚙️ Features
- Preprocessing of IPL match dataset  
- Exploratory Data Analysis (EDA) with visualizations  
- Training machine learning models for win prediction  
- Calculation of win probability based on match state  
- Interactive predictions via Jupyter Notebook  

---

## 📊 Data
The dataset contains ball-by-ball or match summary details of IPL matches, including:
- Batting team, bowling team  
- Current score, overs completed, wickets lost  
- Runs required, target score  
- Match result  

*(Ensure you have the dataset CSV file in the working directory before running the notebook.)*

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ipl-win-probability.git
   cd ipl-win-probability
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook:
   ```bash
   jupyter notebook IPL_Win_Prob.ipynb
   ```
4.output :https://didactic-spork-jjqvv44xj79qc54wg-8501.app.github.dev/

---

## 📦 Requirements
See `requirements.txt` for dependencies:
- numpy  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  
- jupyter  

---

## 📈 Future Improvements
- Build a web app (using **Streamlit**) for interactive predictions  
- Deploy as an API for real-time match updates  
- Train models on updated IPL datasets for improved accuracy  

---

## 📜 License
This project is for educational purposes only and not affiliated with the IPL.
