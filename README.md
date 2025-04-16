cd ~/DSA-StudyBot

# Create the virtual environment (correct this time)
python3 -m venv SLN

# Activate it
source SLN/bin/activate

# Upgrade pip and install everything
pip install --upgrade pip
pip install -r requirements.txt
pip install matplotlib
pip install google-generativeai
pip install streamlit

# Run the app
streamlit run main.py
