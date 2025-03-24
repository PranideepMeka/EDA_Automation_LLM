# EDA_Automation_LLM
Eda integrations using MISTRAL LLM by OLLAMA and Gradio UI[Front End]

# 🔍 AI-Powered EDA & Data Visualization with LLM 📊  

This project automates **Exploratory Data Analysis (EDA)** using **Mistral (LLM)** to generate **AI-powered insights** along with **data visualizations**. The tool is built with **Gradio** for an interactive UI.  

## 🚀 Features  
✅ **Automatic EDA Report**: Provides dataset summary, size, shape, missing values, and AI-generated insights.  
✅ **Data Cleaning**: Handles missing values for numerical and categorical columns.  
✅ **Visualizations**: Generates histograms and correlation heatmaps.  
✅ **AI-Powered Insights**: Uses **Mistral (LLM)** to generate key takeaways from the dataset.  
✅ **Gradio UI**: User-friendly web interface for seamless data exploration.  

## 📌 Installation  
Ensure you have Python installed (3.8+ recommended).  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Insatllation Dependenceis:
pip install -r requirements.txt

Run the Gradio App
bash
Copy
Edit
python app.py
This will launch the Gradio UI in the browser where you can upload a CSV file for analysis.

🛠 How It Works
🧹 Data Preprocessing & Cleaning
Numerical Columns: Missing values filled with column mean.

Categorical Columns: Missing values filled with mode.

📊 Exploratory Data Analysis (EDA)
Dataset Summary (Pandas .describe())

Dataset Info (df.info())

Dataset Size & Shape

Missing Value Report

🔎 AI-Powered Insights (LLM - Mistral)
A prompt is created from the EDA summary and passed to Mistral to generate insights.

📈 Data Visualizations
Histograms for numerical features.

Heatmap showing feature correlations.

📷 Screenshots
🎨 Gradio UI Interface (Upload a screenshot of the UI here)
📊 Generated EDA Report (Upload a sample report here)
🤝 Contribution


📜 License
This project is open-source and available under the MIT License.

🌟 Acknowledgments
This project leverages:

Pandas for data processing

Seaborn & Matplotlib for visualization

Mistral LLM for AI insights

Gradio for building the UI









