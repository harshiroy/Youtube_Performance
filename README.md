📊 YouTube Performance Analysis
A Streamlit-based web application that analyzes YouTube channel/video performance data. It helps creators and analysts visualize metrics like views, likes, comments, and engagement trends to optimize content strategies.

🚀 Features
📂 Upload YouTube analytics CSV/JSON data.
📈 Visualize trends in views, likes, comments, and engagement.
🏆 Identify top-performing and underperforming videos.
🎨 Interactive charts and dashboards.
⚡ Easy-to-use interface built with Streamlit.
🛠️ Tech Stack
Python – Core programming language
Streamlit – Web application framework
Pandas – Data analysis & manipulation
Matplotlib / Seaborn / Plotly – Data visualization
⚙️ Installation
1. Clone the repository
git clone <your-repo-url>
cd youtube-performance-analysis
2. Create and activate a virtual environment
python -m venv venv
Windows
venv\Scripts\activate
Mac/Linux
source venv/bin/activate
3. Install dependencies
pip install -r requirements.txt
If requirements.txt is missing, install manually:

pip install streamlit pandas matplotlib seaborn plotly numpy
▶️ Usage<img width="1000" height="600" alt="feature_importance" src="https://github.com/user-attachments/assets/2705d774-bd69-4c94-aac9-d25dcd33e5e8" />

Run the Streamlit app with:
<img width="1200" height="800" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/65df0794-7765-42f0-9f56-605c4e1f4449" />

streamlit run app.py
Open the browser window that Streamlit launches (usually http://localhost:8501).
Upload your YouTube analytics file.
Explore the interactive charts and insights.
📸 Screenshots
Correlation_heatmap Feature importance plot Revenue_distribution Revenue_vs_views

