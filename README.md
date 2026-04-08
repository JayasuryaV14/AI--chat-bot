🤖 AI Chatbot Web App

A simple and interactive AI-powered chatbot built using Python and a lightweight web framework. This project demonstrates how to integrate a free AI API with a backend server and display real-time responses on a single-page web interface.

🚀 Features
💬 Real-time chatbot interaction
⚡ Fast response using external AI API
🌐 Single-page responsive UI
🧠 Backend powered by Python
🔗 API integration for AI-generated replies
☁️ Deployment-ready with Procfile
🛠️ Tech Stack
Frontend: HTML, JavaScript
Backend: Flask
API: Free AI API (OpenRouter / HuggingFace / Groq)
Deployment: Compatible with platforms like Render / Heroku
📁 Project Structure
project/
│
├── templates/
│   └── index.html      # Frontend UI
│
├── app.py              # Flask backend server
├── Procfile            # Deployment configuration
├── requirements.txt    # Python dependencies
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Add API Key

Open app.py and replace:

API_KEY = "your_api_key_here"

with your actual API key.

4️⃣ Run the Application
python app.py

Open your browser and go to:

http://127.0.0.1:5000
🔄 How It Works
User enters a message in the chat interface
The frontend sends the message to the Flask backend
Backend calls the AI API
AI response is received and sent back
Chat UI updates dynamically
☁️ Deployment

This project includes a Procfile, making it ready for deployment on platforms like:

Render
Heroku
Railway
📌 Future Enhancements
🧾 Chat history storage
🌙 Dark mode UI
⌨️ Enter key support
🔄 Loading animation
🔐 Secure API key management using environment variables
💼 Use Case

This project is ideal for:

Learning API integration
Understanding client-server architecture
Building beginner-friendly AI applications
Showcasing in portfolio and placements
🙌 Acknowledgements
Free AI APIs for enabling chatbot functionality
Open-source community for tools and inspiration
📬 Contact

Feel free to connect or contribute to this project!
