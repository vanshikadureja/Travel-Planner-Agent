# 🧳 Travel Planner Agent – AI-powered Trip Assistant

📌 Project Overview

The  Travel Planner Agent is an AI-powered assistant built on **IBM Cloud** using the **granite-3-3b-instruct** model. It helps users efficiently plan trips by generating personalized travel itineraries based on inputs like destination, budget, trip duration, and preferences.

This agent uses the power of instruction-following LLMs to understand user requests in natural language and return smart, context-aware responses.


# 🚀 Key Features

- 🧠 **Powered by granite-3-3b-instruct**: Leverages IBM’s instruction-tuned model for accurate and contextually rich responses.
- 🗺️ **Trip Itinerary Generator**: Creates day-wise travel plans based on destination and number of days.
- 💬 **Conversational Interface**: Users can interact naturally by typing questions or instructions.
- 🧳 **Budget-Friendly Suggestions**: Recommends destinations, transport, and accommodation based on constraints.
- 🛠️ **Customizable & Scalable**: Easily deployable and extendable via IBM Cloud services.
- 📋 **Static Recommendations**: Provides travel plans without relying on real-time API data.
- 🧩 **Modular Architecture**: Ready to integrate with databases, export options (PDF), or notification services.

---

## 📚 Problem Statement

- Design and implement an **AI-powered Travel Planner Agent** that simplifies the process of trip planning.
- The agent should:
  - Suggest destinations and attractions based on user preferences.
  - Generate structured itineraries based on input like days, interests, and budget.
  - Recommend transport and accommodation options from a static knowledge base.
  - Allow users to interact through natural language inputs.
- Real-time data is not used. The model relies on its pre-trained understanding to offer recommendations.
- The solution should be scalable, secure, and deployable via IBM Cloud infrastructure.

---

## 🧰 Technologies Used

| Technology       | Description                                         |
|------------------|-----------------------------------------------------|
| IBM Cloud        | Cloud platform for deployment and management        |
| Granite-3B Model | IBM foundation model used for natural language tasks|
| Watsonx.ai       | Used for prompt-based interaction with the model    |
| Node.js / Python | Backend server logic (if implemented)               |
| JSON/REST API    | Input/output structure between frontend & backend   |
| IBM Cloud Functions| Serverless backend logic               |

---

## 🛠️ Future Enhancements

- ✅ Export itinerary as PDF or text file
- ✅ Save trip history per user
- 🔄 Add login & session handling
- 📤 Email/WhatsApp integration for sharing plans
- 🔍 Add feedback & rating module for suggested plans

## 📂 Folder Structure (Sample)

