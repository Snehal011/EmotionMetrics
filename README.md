# 🧠 EmotionMetrics – Emotion Analytics Platform

EmotionMetrics is a web-based emotion analytics platform designed to analyze facial expressions and provide insights into students' emotional well-being. The platform combines **deep learning-based facial emotion recognition** with interactive dashboards and questionnaires to support emotion tracking and well-being analysis.

The project was developed as part of a research initiative focused on exploring technology-assisted approaches to student well-being.

---

## ✨ Features

* 🧠 **Facial Emotion Recognition**
  Uses a deep learning model to identify emotions from facial expressions.

* 📊 **Emotion Analytics Dashboard**
  Visualizes emotion-related data through interactive charts and insights.

* 😊 **Happiness Index**
  Provides an aggregated measure based on collected emotional and questionnaire data.

* 📝 **Well-Being Questionnaires**
  Includes questionnaires designed to collect additional information related to emotional well-being.

* 💬 **Interactive Chatbot**
  Provides a conversational interface for engaging users with emotion and well-being related interactions.

* 📈 **Session-Based Insights**
  Displays emotion trends and confidence information across user sessions.

---

## 🛠️ Tech Stack

### Frontend

* React
* JavaScript
* HTML5
* CSS3
* Chart.js

### Machine Learning

* Python
* Convolutional Neural Network (CNN)
* ResNet-50
* Facial Expression Recognition

### Dataset

* CK+
* FER2013

### Database

* MongoDB Atlas

---

## 🏗️ System Architecture

```text
                 User
                  │
                  ▼
          EmotionMetrics Web App
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
 Facial Expression      Questionnaires
      Input                  │
        │                    │
        ▼                    │
   CNN / ResNet-50           │
        │                    │
        ▼                    ▼
 Emotion Prediction ───► Data Processing
        │                    │
        └─────────┬──────────┘
                  ▼
           Emotion Analytics
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
    Happiness   Trends   Confidence
      Index     Charts     Scores
        │         │         │
        └─────────┼─────────┘
                  ▼
          MongoDB Atlas
```

---

## 📱 Application Modules

### 🏠 Dashboard

Provides an overview of collected emotional data and key insights.

### 😊 Emotion Detection

Processes facial expressions and predicts the corresponding emotional category.

### 📊 Emotion Analytics

Displays emotion trends, confidence scores, and session-level visualizations.

### 📝 Questionnaires

Collects user responses to complement facial emotion analysis.

### 💬 Chatbot

Provides an interactive conversational interface related to emotional well-being.

---

## 🧠 Machine Learning

The project uses a **Convolutional Neural Network (CNN)** approach for facial emotion recognition, with **ResNet-50** used as the underlying deep learning architecture.

The model is trained/evaluated using publicly available facial expression datasets, including:

* **CK+**
* **FER2013**

The predicted emotions are integrated with the application's analytics layer to generate visual insights.

---

## 📊 Data Visualization

EmotionMetrics uses interactive visualizations to represent:

* Emotion distribution
* Emotion trends across sessions
* Prediction confidence
* Happiness Index
* Questionnaire-based insights

**Chart.js** is used to create interactive charts within the web application.

---

## 🗄️ Database

**MongoDB Atlas** is used for storing and managing application data, including relevant session and questionnaire information.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* Python
* Git
* MongoDB Atlas account

### Clone the Repository

```bash
git clone <repository-url>
```

### Navigate to the Project

```bash
cd EmotionMetrics
```

### Install Frontend Dependencies

```bash
npm install
```

### Start the Development Server

```bash
npm start
```

---

## 🔐 Environment Variables

Create a `.env` file and add the required configuration values for your application.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
```

> Do not commit API keys, database credentials, or other sensitive information to the repository.

---

## 🎯 Project Objectives

* Explore the use of deep learning for facial emotion recognition.
* Provide an interactive platform for visualizing emotional data.
* Combine facial emotion analysis with questionnaire-based insights.
* Develop technology-assisted approaches to understanding student well-being.
* Present emotion-related information through accessible dashboards and visualizations.

---

## 🔮 Future Enhancements

* Improve emotion recognition accuracy with larger and more diverse datasets.
* Add personalized emotion and well-being reports.
* Introduce additional visualization and analytics features.
* Enhance the chatbot with more contextual interactions.
* Add longitudinal emotion tracking and trend analysis.
* Improve model performance for real-world environmental conditions.

---

## ⚠️ Disclaimer

EmotionMetrics is a **research and educational project** intended to explore emotion analytics and technology-assisted well-being insights.

The system's emotion predictions and generated insights should **not be considered medical, psychological, or clinical diagnoses**.

---
