# Recipe-Preparation-Agent-
SmartChef AI is an AI-powered Recipe Preparation Agent built using IBM Orchestrate and IBM Cloud Lite. It uses RAG to recommend recipes based on available ingredients, provides step-by-step cooking instructions, suggests ingredient substitutions, supports dietary preferences, and helps reduce food waste by turning pantry items into delicious meals.
# 🍳 SmartChef AI – Recipe Preparation Agent

## 📌 Project Overview

SmartChef AI is an AI-powered Recipe Preparation Agent that helps users prepare delicious meals using the ingredients they already have at home. Built with **IBM watsonx.ai**, **IBM watsonx Orchestrate**, and **Retrieval-Augmented Generation (RAG)**, the agent retrieves relevant recipes from a knowledge base and generates personalized cooking instructions, ingredient substitutions, nutritional insights, and cooking tips.

The solution aims to reduce food waste, save time, and make everyday cooking simpler through an intelligent conversational assistant.

---

## ✨ Features

* 🥗 Recipe recommendations based on available ingredients
* 🤖 AI-powered conversational cooking assistant
* 🔍 Retrieval-Augmented Generation (RAG)
* 🍅 Ingredient substitution suggestions
* 🥦 Support for dietary preferences and allergies
* ⏱️ Cooking and preparation time estimates
* 📊 Basic nutritional information
* 🍽️ Step-by-step cooking guidance
* 💬 Natural language interaction using IBM watsonx Orchestrate

---

## 🛠️ Technology Stack

### AI Platform

* IBM watsonx.ai
* IBM watsonx Orchestrate

### Knowledge & Retrieval

* Retrieval-Augmented Generation (RAG)
* Recipe Knowledge Base
* Vector Search

### Cloud Services

* IBM Cloud Lite
* IBM Cloud Object Storage

### Frontend

* HTML5
* CSS3
* JavaScript

---

## 🧠 System Workflow

1. User enters available ingredients.
2. IBM watsonx Orchestrate receives the request.
3. The RAG pipeline searches the recipe knowledge base.
4. Relevant recipes are retrieved.
5. IBM Orchestrate generates a personalized response.
6. The chatbot provides:

   * Recommended recipe
   * Step-by-step instructions
   * Ingredient substitutions
   * Nutrition summary
   * Cooking tips

---

## 📂 Project Structure

```
SmartChef-AI/
│
├── README.md
├── LICENSE
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── knowledge_base/
│   ├── recipes.json
│   ├── recipes.csv
│   └── recipe_documents/
│f
```

## 🚀 How It Works

SmartChef AI uses IBM watsonx Orchestrate as the conversational backend. When a user submits available ingredients, the orchestrated workflow retrieves the most relevant recipes from the knowledge base using RAG. IBM Orchestrate then generates a personalized response containing cooking instructions, substitutions, preparation tips, and nutritional information. The entire interaction happens through a natural language chatbot, providing an intuitive and engaging user experience.

---

## 🎯 Objectives

* Reduce household food waste
* Provide personalized recipe recommendations
* Support healthy and dietary-specific meal planning
* Simplify cooking through conversational AI
* Demonstrate the practical use of IBM Cloud and IBM watsonx Orchestrate

---

## 🔮 Future Enhancements

* Voice-enabled cooking assistant
* Image-based ingredient recognition
* Barcode scanning for groceries
* Weekly meal planner
* Smart grocery recommendations
* Multi-language support
* Mobile application

---

## 📜 License

This project is released under the MIT License.

---

## 🙏 Acknowledgements

* IBM watsonx.ai
* IBM watsonx Orchestrate
* IBM Cloud Lite
