# 🌾 Smart Farming AI Agent

An AI-powered multilingual assistant designed to support small-scale farmers with real-time, localized agricultural guidance. Built using IBM Watsonx.ai and Retrieval-Augmented Generation (RAG), this agent delivers insights on crop selection, weather, soil health, mandi prices, and pest control—accessible in English, Hindi, Punjabi, French, and more.

---

## 🧩 Problem Statement

Small and marginal farmers often lack access to timely, location-specific agricultural advice. They struggle to make data-informed decisions about crop planning, pest control, market pricing, and climate patterns, leading to low yields and income instability.

---

## 💡 Proposed Solution

A smart AI agent hosted on IBM Cloud that uses Watsonx.ai and RAG to provide multilingual, data-driven farming recommendations. By combining structured datasets (soil, weather, mandi prices) with natural language interaction, the agent empowers farmers with accurate and context-aware advice.

---

## 🧠 Technologies Used

- IBM Watsonx.ai Studio
- IBM Granite Foundation Model
- Watsonx Runtime
- Retrieval-Augmented Generation (RAG)
- FAISS or Vector Index for dataset retrieval
- Python for tool integration
- CSV datasets (Soil, Weather, Crop Production, Mandi Prices)

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio
- IBM Granite Model
- Watsonx Runtime
- IBM Cloud Object Storage
- IBM Cloud IAM

---

## 👥 End Users

- Small and marginal farmers  
- Agri-tech startups and field agents  
- Government agricultural extension centers  
- NGOs and rural development organizations  
- Students in agriculture and soil sciences

---

## 🌟 WOW Factors

- Multilingual support: responds in English, Hindi 
- Uses real-time soil, crop, and mandi datasets for recommendations  
- Powered by IBM Watsonx and Retrieval-Augmented Generation (RAG)  
- Smart redirection on off-topic queries  
- Can personalize advice based on district-level input data  

---

## 🧪 Key Features

- Data-grounded answers on farming topics  
- Live mandi price insights  
- Personalized crop suggestions based on soil type and weather  
- Multilingual query understanding and responses  
- Real-world dataset ingestion (CSV files for soil, weather, etc.)

---

## 🚀 How It Works

1. Farmer asks a question in their native language  
2. Granite model processes the query using Watsonx.ai  
3. Vector Index retrieves data from uploaded soil/weather/mandi datasets  
4. AI agent provides a concise, language-specific response  
5. Response grounded in real uploaded data (RAG enabled)

---

## 📸 Screenshots

> (https://github.com/tecmeckc/Smart_Farmer_AI_Agent/blob/main/SmartFarming.png)
> (https://github.com/tecmeckc/Smart_Farmer_AI_Agent/blob/main/previewFinal.png)
> (https://github.com/tecmeckc/Smart_Farmer_AI_Agent/blob/main/Deployed.png)
> (https://github.com/tecmeckc/Smart_Farmer_AI_Agent/blob/main/randomPrompt.png)

- Agent setup and deployment  
- Dataset upload (Soil, Weather, Mandi Prices)  
- Query and Response in multiple languages  


---

## 📌 How to Run or Deploy

1. Log in to IBM Cloud Lite: https://cloud.ibm.com  
2. Launch Watsonx.ai Studio and create a new project  
3. Upload datasets (CSV files) to Vector Index  
4. Configure agent instructions and tools  
5. Deploy agent using Watsonx Runtime  
6. Test via built-in panel or Postman using deployment endpoint  

---

## 🛣️ Future Scope

- Voice-based query support (speech-to-text integration)  
- WhatsApp chatbot and mobile app deployment  
- Real-time IoT sensor data integration (soil moisture, temperature)  
- AI-based pest/disease alerts  
- Expansion to more regional languages  

---

## ⚖️ License

This project is licensed under the MIT License.

---

> Created during the IBM SkillsBuild for Academia Internship 2025 by **Khyati Choudhary**
