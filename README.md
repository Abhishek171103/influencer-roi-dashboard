# 📈 Influencer Campaign ROI Dashboard

A Streamlit-based web dashboard to visualize the performance and ROI (Return on Ad Spend) of influencer marketing campaigns. It helps marketing teams evaluate influencer impact, optimize spends, and identify top performers.

---

## 🚀 Features

- Filter influencers by **platform** (e.g., Instagram, YouTube) and **category** (e.g., Fitness, Lifestyle)
- View **overall campaign summary**: total revenue, orders, spend, and average ROAS
- Identify **top influencers** based on revenue and ROAS
- Detect **underperforming influencers** with ROAS less than 1
- Fully interactive dashboard built with **Streamlit**

---

## 📁 Project Structure

📦 campaign-roi-dashboard

├── app.py # Main Streamlit app

├── influencers.csv # Influencer master data

├── posts.csv # Post-wise tracking data

├── tracking_data.csv # Campaign performance metrics

├── payouts.csv # Payout info for influencers

└── README.md # Project description and setup

## 🔧 Setup Instructions

### 🖥️ Option 1: Run Locally

#### Prerequisites:
- Python 3.8+
- Install required packages: pip install streamlit pandas
Run the app:
- streamlit run app.py
- It will open in your browser at: http://localhost:8501

### 🌐 Option 2: Run on Google Colab with ngrok (if you don’t have local setup)
- Upload all files (app.py, 4 CSVs)

- Install Streamlit and pyngrok in Colab:  !pip install streamlit pyngrok
- Use ngrok to expose the app: from pyngrok import ngrok
- !streamlit run app.py &
- public_url = ngrok.connect(8501)
- print("Streamlit App URL:", public_url)
- Then click on the printed https://2c55846a8e79.ngrok-free.app/ URL.

### 📊 Sample Use Cases
- Track campaign-level ROI
- Spot high-performing influencers
- Optimize payouts vs returns
- Guide future influencer collaborations

### 🧑‍💻 Author
Abhishek Jain
This dashboard is built as part of a performance marketing and data visualization assessment project.

### 📝 License
This project is for educational/demo purposes only. All data used is sample data.
