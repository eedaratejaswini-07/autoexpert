# 🚗 AutoSage  
## Multimodal AI Vehicle Intelligence System  

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red)
![Google Gemini](https://img.shields.io/badge/Google-Gemini_2.5_Flash-orange)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

AutoSage is a **multimodal AI-powered automotive intelligence system** built using **Google Gemini 2.5 Flash**.  
The application provides structured vehicle insights from images and supports automotive advisory queries via a domain-restricted AI assistant.

Developed as part of a **Google Cloud – Generative AI Internship**, this project demonstrates real-world implementation of:

- Multimodal AI integration  
- Prompt engineering  
- Secure API handling  
- Domain restriction logic  
- Real-time Streamlit deployment  

---

## 📌 Problem Statement

Modern vehicle buyers often face challenges in:

- Identifying vehicle models from images  
- Understanding technical specifications clearly  
- Comparing maintenance and resale value  
- Selecting eco-friendly vehicle options  
- Making informed purchasing decisions  

There is a need for a structured, AI-driven automotive intelligence assistant that simplifies vehicle decision-making.

---

## 🎯 Project Objectives

- Implement image-based vehicle recognition using Gemini multimodal capabilities  
- Generate structured automotive insights  
- Restrict chatbot responses strictly to automotive domain  
- Provide budget-based and comparison-based recommendations  
- Deploy as a real-time interactive web application  

---

## 🔍 Core Modules

### 1️⃣ Image-Based Vehicle Analysis Module

Users upload a vehicle image and receive structured insights including:

- Brand & Model Identification  
- Launch Year  
- Vehicle & Fuel Type  
- Engine & Performance Specifications  
- Mileage & Price Range (INR)  
- Maintenance Level  
- Safety Features  
- Target Audience  
- Estimated 10-Year Resale Value  
- Market Positioning Summary  

Structured prompt engineering ensures consistent formatting and professional output generation.

---

### 2️⃣ Automotive AI Advisory Assistant

The text-based assistant supports:

- Budget-based vehicle recommendations  
- Model comparisons  
- EV & Hybrid suggestions  
- Seasonal maintenance advice  
- Simplified explanation of technical terms  

The assistant is **domain-restricted**, ensuring it only responds to automotive-related queries.

---

## ⚙️ Why Gemini 2.5 Flash?

Gemini 2.5 Flash was selected due to:

- Fast multimodal processing  
- Low latency inference  
- Cost-efficient API usage  
- Strong structured response generation  
- Reliable image + text understanding  

---

## 🏗 System Architecture

```
User Input (Image / Text)
        ↓
Streamlit Frontend
        ↓
Prompt Engineering Layer
        ↓
Gemini 2.5 Flash API
        ↓
Structured Insight Engine
        ↓
Formatted Response Display
```

---

## 🛠 Technology Stack

- Python  
- Streamlit  
- Google Gemini 2.5 Flash API  
- Prompt Engineering  
- Multimodal AI  
- python-dotenv (Secure API Management)  

---

## 🧪 Testing & Validation Strategy

The system was validated using:

- Image format validation (JPEG / PNG)  
- Non-vehicle image handling  
- Domain restriction enforcement  
- Conditional UI rendering tests  
- Structured output consistency checks  
- API error handling validation  

---

## 📸 Application Screenshots

### 🏠 Home Interface
![Home Screen](Assets_for_ReadmeFile/home.png)

---

## 🚗 Four-Wheeler Analysis

### 📷 Analysis Output – Part 1
![Four Wheeler 1](Assets_for_ReadmeFile/four_Wheeler_image_analysis/image1.jpg)

### 📊 Analysis Output – Part 2
![Four Wheeler 2](Assets_for_ReadmeFile/four_Wheeler_image_analysis/image2.jpg)

### 📈 Analysis Output – Part 3
![Four Wheeler 3](Assets_for_ReadmeFile/four_Wheeler_image_analysis/image3.jpg)

---

## 🏍 Two-Wheeler Analysis

### 📷 Analysis Output – Part 1
![Two Wheeler 1](Assets_for_ReadmeFile/two_wheeler_image_analysis/image1.jpg)

### 📊 Analysis Output – Part 2
![Two Wheeler 2](Assets_for_ReadmeFile/two_wheeler_image_analysis/image2.jpg)

---

## 🤖 Automotive AI Assistant
![Chatbot](Assets_for_ReadmeFile/chatbot.png)

---

## 🚀 Live Deployment

🔗 **Streamlit App:**  
https://autosage-app-gp4curmwapppp2edzadnwdta.streamlit.app/

---

## 🎥 Project Demonstration

🔗 **Demo Video:**  
https://drive.google.com/file/d/1rrwIvtJkw4qBJb4GAjfqua2YbGsxRw4e/view?usp=drive_link

---

## 📂 Project Structure

```
AUTOEXPERT
│
├── Project_Files
│   ├── app.py
│   ├── requirements.txt
│   ├── .env
│   └── images
│       ├── image1.png
│       ├── image2.png
│       ├── image3.jpeg
│       ├── image4.png
│       ├── image5.png
│       └── image6.png
│
├── Assets_for_ReadmeFile
│   ├── home.png
│   ├── chatbot.png
│   ├── four_Wheeler_image_analysis
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── image3.jpg
│   │
│   └── two_wheeler_image_analysis
│       ├── image1.jpg
│       └── image2.jpg
│
├── Project_Template
│   ├── 1. Ideation Phase
│   ├── 2. Requirement Analysis
│   ├── 3. Project Design Phase
│   ├── 4. Project Planning Phase
│   ├── 5. Project Development Phase
│   ├── 6. Project Documentation
│   └── 7. Project Demonstration
│
├── Video Demo
│   └── AutoSage Demo  Video
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation Guide

Follow the steps below to run the AutoSage application locally.

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/eedaratejaswini-07/autoexpert.git
cd autoexpert
```

---

### 2️⃣ Navigate to Project Directory

```bash
cd Project_Files
```

---

### 3️⃣ Install Dependencies

Install all required Python libraries:

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Configure Environment Variables

Create a `.env` file inside the **Project_Files** directory.

```
Project_Files/.env
```

Add your **Google Gemini API key** inside the file:

```
GOOGLE_API_KEY=your_api_key_here
```

⚠️ Ensure `.env` is listed in `.gitignore` to keep the API key secure.

---

### 5️⃣ Run the Application

Start the Streamlit web application:

```bash
streamlit run app.py
```

After running the command, the application will automatically open in your browser.

If it does not open automatically, visit:

```
http://localhost:8501
```

---
## ⚠️ Limitations

- Accuracy depends on image quality and camera angle.  
- Vehicle details are AI-generated and may contain estimated values.  
- Requires a stable internet connection to access the Gemini API.  
- Limited by API usage quotas.  
- Assistant responses are restricted to automotive-related queries only.

---

## 🔮 Future Enhancements

- Integrate real-time automotive databases for accurate specifications and pricing.  
- Add VIN-based vehicle identification.  
- Support voice-based interaction.  
- Improve vehicle recognition accuracy using advanced models.  
- Develop a mobile application for wider accessibility.

---

## 📘 Documentation

Complete project documentation available in:

```
Project_Template/6. Project Documentation/Final_Report.pdf
```

---

## 👩‍💻 Developers

**Eedara Tejaswini**  
**Prasanna Kumar Raparla**  
**Sai Kumar Ramoju**  
**Sandeep Peruri**  

Google Cloud – Generative AI Internship  

---

## 📜 License

This project is developed for **educational and internship purposes only**.
