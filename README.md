# 🧠 AI Meal Planner with Gemini 2.0

Welcome to the **AI Meal Planner**, an intelligent nutrition assistant powered by **Gemini 2.0**. This project leverages Google’s advanced language model to help users plan healthy, personalized meals and monthly diets using image inputs, nutrient analysis, and structured API responses.

---

## 🚀 Features

### 📸 Image-Based Meal Recognition
- Upload a photo of your meal
- Gemini 2.0 processes the image and returns structured **JSON data** of detected food items and **nutritional content** (calories, protein, carbs, etc.)

### 📊 Smart Nutrition Matching
- Uses a **Kaggle nutritional dataset** to recommend foods closest to your dietary needs
- Matches based on user-specified nutrients: calories, protein, fiber, fats, and more

### 📅 Personalized Monthly Diet Planner
- Input your goals and preferences (e.g. high protein, low carbs)
- Gemini generates a **structured JSON** monthly diet plan tailored to your needs

---

## 🛠️ Technologies Used
- 🧠 **Gemini 2.0 API** – Natural language + vision model for meal recognition and response generation
- 📁 **Kaggle Dataset** – Nutrition information from Food-101 and related food sources
- 🐍 **Python** – Core backend and API interaction
- 📦 **Pandas, NumPy** – For data analysis and nutrient similarity calculations
- 🧾 **Structured JSON** – Used for clear, programmable API responses and user preferences

---

## 🖼️ Sample Flow
1. **User uploads a meal image**
2. **Gemini returns nutritional breakdown in structured JSON**
3. **User sets dietary goals**
4. **AI recommends top foods and generates a monthly plan**

---

## 📷 Example Output
```json
{
  "meal_items": ["grilled chicken", "steamed broccoli", "brown rice"],
  "nutrients": {
    "calories": 450,
    "protein": 38,
    "carbohydrates": 40,
    "fats": 12,
    "fiber": 5
  }
}
```

---

## 💡 Use Cases
- 🏋️‍♂️ Fitness and bodybuilding meal tracking  
- 🧘 Personalized diet management  
- 🥗 Smart grocery planning based on nutrient gaps  
- 🤖 Building intelligent nutrition coach apps

---

## 📦 Dataset
The project uses the **Food-101 Nutrition Dataset** available from Kaggle, which provides a comprehensive nutrient breakdown for a wide range of food items.
