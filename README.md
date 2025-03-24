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


LLM-Powered EDA Analysis with Gradio and Ollama
Project Overview
This project integrates Ollama, an open-source framework for running large language models (LLMs) locally, with Gradio, a user-friendly web interface, to automate Exploratory Data Analysis (EDA). The application allows users to upload a dataset and receive an AI-generated summary, key insights, and visualizations.

Installation and Setup
Step 1: Installing Ollama
Ollama, a lightweight framework for running LLMs, was downloaded and installed from the official website: https://ollama.ai.

Step 2: Extracting Mistral LLM
Once Ollama was set up, the Mistral open-source LLM was extracted and used for generating insights.

Other Open-Source LLMs Available in Ollama
In addition to Mistral, Ollama supports various open-source LLMs, including:

Llama 2 (Meta)

Gemma (Google DeepMind)

Phi (Microsoft)

Code Llama (for code generation)

Mixtral (Mixture of Experts model)

Project Workflow
Data Upload: Users upload a CSV dataset.

Data Cleaning: Missing values are handled automatically.

EDA Generation: The dataset’s summary, shape, size, and structure are extracted.

LLM Insights: A prompt is created and passed to the Mistral model for insights.

Data Visualization: Histograms and correlation heatmaps are generated.

Gradio UI: The app runs on a live link for 72 hours, allowing users to interact.

Live Deployment
After running the Gradio UI, a live link is generated, valid for 72 hours. Users can access this link to upload datasets and receive automated EDA reports.

Future Developments
While basic functionalities are implemented, further improvements are required:

Enhanced Data Cleaning (outlier detection, advanced imputation)

More Visualization Options (boxplots, scatter plots)

Improved LLM Insights (pattern detection, anomaly detection)

Cloud Deployment for permanent access

How to Run the Project
Requirements
Install dependencies from requirements.txt:

bash
Copy
Edit
pip install -r requirements.txt
Run the Application
bash
Copy
Edit
python app.py
Expected Output
Dataset Summary

Key Insights from Mistral

Histograms & Correlation Heatmaps

Gradio UI Link for Interaction

Conclusion
This project demonstrates the power of LLMs in automated data analysis, leveraging Mistral for insights and Gradio for an interactive UI. Future enhancements will improve usability, scalability, and analysis depth.










