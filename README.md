WhatsApp Chat Analyser 📊
A Streamlit web app to analyze WhatsApp chat exports and visualize group or personal chat activity through various insights like message counts, timelines, word clouds, and emoji usage.

🚀 Features
📅 Analyze WhatsApp chat exports (.txt format)

👥 Identify the most active users

⏰ See activity timelines and message patterns

☁️ Generate word clouds for most-used words

😂 Analyze emoji usage

🔗 Extract links shared in the chat

📊 Visualize results using Matplotlib and Seaborn

🛠️ Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/kshttij/whatsapp-chat-analyser.git
cd whatsapp-chat-analyser
2. Create and Activate a Virtual Environment
bash
Copy
Edit
python -m venv .venv
.\.venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
▶️ Usage
Run the Streamlit app:

bash
Copy
Edit
streamlit run main.py
Then open your browser at:
http://localhost:8501

📥 Exporting WhatsApp Chat
Open the WhatsApp chat or group you want to analyze.

Tap on "More" → "Export Chat" → "Without Media".

Save the generated .txt file and upload it in the app.

🌟 Example Insights
Most active users

Word cloud of frequently used words

Emoji usage frequency

Daily, monthly, and hourly activity timelines

Shared links and their counts

🔧 Tech Stack
Python 3.10

Streamlit

Pandas

Matplotlib

Seaborn

WordCloud

URLExtract

🤝 Contributions
Pull requests are welcome!
If you'd like to improve this project, please fork the repo and submit a pull request.

📜 License
This project is licensed under the MIT License.

