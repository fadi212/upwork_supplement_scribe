# 🌿 **Supplement Generator Project** – Personalized Health, Simplified

## 🚀 **About the Project**
Welcome to the **Supplement Generator Project**, a smart healthcare assistant designed to help users make **informed decisions about their health**. This project combines **AI-driven supplement recommendations**, an **interactive chatbot assistant**, and **automated medical report analysis** to create a seamless experience for users looking to optimize their wellness.

### 💡 **Why This Project?**
Navigating the world of health and wellness can be overwhelming. With endless supplement choices, complex medical reports, and scattered information, making the right decision can feel impossible. This project is here to **bridge that gap** by offering **personalized, data-driven guidance** tailored to each user’s unique health needs.

---

## 🏗️ **Core Components**

### 🧪 **1. Supplement Generator Module**
🔹 The heart of this project! It **analyzes user data** and **personal health concerns** to create **custom supplement plans**.  
🔹 Extracts **supplement names & brands** and finds **where to buy them** using **Tavily Search**.  
🔹 Ensures that recommendations align with medical conditions, dietary restrictions, and health goals.  

✨ *Example: If a user lacks Vitamin D (based on their medical report), the system recommends top-rated Vitamin D supplements along with dosage instructions!*  

---

### 🤖 **2. Chatbot Assistant – Your Personal AI Health Guide**
🔹 Interacts with users to **answer healthcare-related queries**, interpret medical reports, and provide recommendations.
🔹 Uses a **user ID** to fetch stored health data from the database and **generate personalized responses** with AI.

✨ *Example: "Hey Chatbot, I have a Vitamin B12 deficiency. What should I do?" → The assistant provides a tailored explanation and recommends supplements accordingly!*  

---

### 📄 **3. PDF File Reader – AI-Powered Lab Report Analysis**
🔹 Processes **S3-hosted medical & genetic reports** to **extract key health insights**.  
🔹 Uses AI to **organize data into a structured JSON format**, identifying **biomarkers, genetic variations, and other crucial details**.  
🔹 Helps users **understand their lab results in a simple, easy-to-read format**.  

✨ *Example: A user uploads a blood test report → The system extracts biomarkers (e.g., Iron, Cholesterol) and provides a clear, AI-generated summary!*  
