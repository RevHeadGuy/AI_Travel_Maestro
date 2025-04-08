# 🗺️ AI Travel Maestro

AI Travel Maestro is an intelligent travel planner that generates **personalized itineraries** based on user preferences. 🚀  
Enter your **city, interests, and trip duration**, and let AI create the perfect **day trip or vacation plan** for you!

## ✨ Features
✅ AI-powered **personalized itineraries**  
✅ Supports **multi-day trips**  
✅ Fetches **city images** dynamically  
✅ User-friendly **Gradio UI**  

## 🛠️ Tech Stack
- **Python** 🐍  
- **LangChain + Groq LLM** 🤖  
- **Gradio** (for UI) 🎨  
- **Graphviz** (for workflow visualization)  
- **Unsplash API** (for images) 🖼️  

## 🚀 Installation
### 1️⃣ Clone the Repository

git clone https://github.com/RevHeadGuy/AI_Travel_Maestro.git

cd AI_Travel_Maestro

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Application

python app.py

🎯 How It Works
Enter your destination (city name)
Specify your interests (e.g., food, adventure, culture)
Set the trip duration
AI generates an itinerary with top attractions & activities
View images for easy navigation

📸 Screenshots

<img width="1440" alt="Screenshot 2025-04-09 at 12 13 19 AM" src="https://github.com/user-attachments/assets/b3699739-085c-4d08-a399-c70f7981d4a5" />

🏗️ Workflow Diagram

mermaid

graph TD;
  A[User Inputs] -->|City, Interests, Days| B[Process Inputs]
  B --> C[Generate Itinerary]
  C --> D[Fetch City Image]
  D --> E[Generate Google Maps Link]
  E --> F[Format Itinerary]
  F --> G[Display Final Itinerary]
  
🔑 API Keys Required

Groq API for LLM

Unsplash API for city images

Google Maps API (optional)

Create a .env file and add:

GROQ_API_KEY=your_api_key_here

UNSPLASH_ACCESS_KEY=your_access_key_here

🤝 Contributing
PRs are welcome! Fork the repo, make changes, and submit a pull request.

📜 License
MIT License © 2025 AI Travel Maestro




