# 🍳 AI Recipe Suggester with Spring Boot + OpenAI

An **AI-powered recipe recommendation system** built with **Spring Boot 3**, **Spring AI**, and **OpenAI GPT-4o**.
This project demonstrates how to integrate **Generative AI** into modern backend applications to create intelligent, context-aware APIs.

---

## 🚀 Features

* 🔥 **AI-Powered Recipe Suggestions** – Generate unique meal ideas instantly.
* 🐟 **Domain-Specific Recipes** – Seafood-only recipe expert.
* 🧑‍🍳 **Conversational AI Chef** – Maintain a conversation history with an AI-powered chef.
* 📋 **Structured Outputs** – Convert AI responses into Lists, Maps, and Custom Java Beans.
* 🌍 **Country-Specific Dishes** – Fetch recipes with country of origin.
* ⚡ **Spring Boot + Spring AI** – Modern backend with minimal boilerplate.

---

## 🛠 Tech Stack

* ☕ **Java 21**
* 🌱 **Spring Boot 3.5.6**
* 🤖 **Spring AI (1.0.3)**
* 🧠 **OpenAI GPT-4o**
* 📦 **Maven**
* 🌐 **REST APIs**

---

## 📡 API Endpoints

### 1. General Recipe Suggestion

`GET /recipes/suggest-recipe?message=Suggest+a+recipe+for+dinner`

### 2. Seafood Recipes

`GET /recipes/sea-food/suggest-recipe?message=Suggest+a+seafood+dish`

### 3. Conversational Chef

`GET /recipes/sea-food/chef/suggest-recipe?message=Suggest+a+shrimp+meal`

### 4. Ingredient-Based Recipes

`GET /recipes/suggester?ingredient=shrimp`

### 5. Country-Specific Recipes

`GET /recipes/suggester/country?ingredient=shrimp`

### 6. Best Recipe (with calories)

`GET /recipes/suggester/best?ingredient=shrimp`

### 7. Best 10 Recipes as List

`GET /recipes/suggester/best-list?ingredient=shrimp`

---



## 📸 Demo (Examples)

```
GET /recipes/suggester?ingredient=shrimp
➡️ [ "Garlic Butter Shrimp", "Shrimp Alfredo Pasta", "Shrimp Tacos", ... ]
```

```
GET /recipes/suggester/best?ingredient=shrimp
➡️ { "name": "Shrimp Scampi", "country": "Italy", "calories": 450 }
```

---

## 🚀 Future Enhancements

* Add **Frontend UI (Angular/React)** for interactive usage.
* Deploy on **AWS / Docker / Kubernetes**.
* Support for **multiple LLM providers**.
* Integration with **Recipe Nutrition APIs**.

---

## 👨‍💻 About Me

👋 Hi, I’m **Ahmed Farag** – a **Full Stack Developer (Spring Boot + Angular)** passionate about building AI-powered applications.

* 💼 LinkedIn: [Ahmed Farag](https://www.linkedin.com/in/ahmed-farag-93a74324a/)
* 🌐 GitHub: [AhmedFarag22](https://github.com/AhmedFarag22)
* 💡 Interests: **Web Development | AI | Cloud**

---
