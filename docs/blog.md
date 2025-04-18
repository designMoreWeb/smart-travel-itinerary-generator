---
layout: post
title: "Smart Travel Itinerary Generator: Plan Your Perfect Trip with AI"
description: "Use Gemini 1.5 Pro and Kaggle to build a chat-powered travel planning assistant that creates and refines personalized itineraries."
date: 2025-04-16
author: "designMoreWeb"
tags: [Gemini, Kaggle, AI, Travel, Capstone, JSON, Google Cloud]
---

# ✈️ Smart Travel Itinerary Generator: Plan Your Perfect Trip with AI

Planning a trip is exciting—but time-consuming. From blog posts to reviews and Reddit rabbit holes, it's easy to spend more time researching than relaxing. So I built something smarter: an AI-powered **Smart Travel Itinerary Generator** that helps you plan your perfect trip through natural conversation.

This capstone project, built in a Kaggle Notebook, uses Google's **Gemini 1.5 Pro** to generate structured, customizable itineraries—then refines them based on follow-up prompts. Whether you want temples, nature, coffee, or vegetarian food, this assistant has you covered.

---

## 💡 Why I Built This

I wanted to explore how **generative AI** could move beyond answering questions to **actively helping users accomplish real-world tasks**—in this case, travel planning.

The goal: create an intelligent assistant that produces high-quality, human-friendly travel plans from just a few lines of input, and continues improving the plan with context-aware conversation.

---

## 🛠️ Tech Stack

| Tool               | Use |
|--------------------|-----|
| 🧠 Google Gemini 1.5 Pro API | Generative AI responses in structured JSON |
| 📓 Kaggle Notebook          | Interactive development & visualization |
| 🧾 Markdown + IPython       | Formatted itinerary display |
| 🌐 GitHub Pages             | Blog and project hosting |

---

## 🧠 GenAI Capabilities Demonstrated

- ✅ **Structured Output / JSON Mode**  
Gemini outputs structured itineraries, which are parsed and displayed as clean day-by-day Markdown plans.

- ✅ **Few-Shot Prompting**  
The assistant learns how to format and structure plans by seeing examples embedded in the prompt.

- ✅ **Simulated Long Context Window**  
While Gemini’s REST API is stateless, I simulate memory by storing a full chat history and feeding it back with every call.

---

## ✨ What It Can Do

- Create multi-day itineraries based on:
  - City
  - Number of days
  - User interests (e.g., temples, coffee, vegetarian food)
- Update specific days:
  - “Make Day 2 more relaxing and include a tea ceremony.”
- Add activities:
  - “Add a morning jog to Day 1.”
- Enhance recommendations:
  - “Include a vegetarian restaurant near Arashiyama.”

The assistant then returns a full updated JSON plan, which is rendered beautifully in the notebook.

---

## 🧪 Sample Output

```markdown
# 🌏 Kyoto 5-Day Adventure

**Destination:** Kyoto  
**Duration:** 5 Days  
**Interests:** Temples, Nature, Vegetarian Food, Coffee  

---

## 📅 Day 1 – Temples and Traditional Kyoto
- 🗺️ Fushimi Inari Shrine (temple): Thousands of red gates
- 🗺️ Kiyomizu-dera Temple (temple): Wooden stage and views
- 🗺️ Gion District (sightseeing): Geishas, traditional streets  
🍽️ Meal Tip: Explore vegetarian restaurants in Gion

## 📅 Day 2 – Relaxing Arashiyama
- 🗺️ Bamboo Grove (nature): Peaceful forest walk
- 🗺️ Tenryu-ji Temple (temple): Zen garden
- 🗺️ Tea Ceremony (cultural): Experience traditional hospitality  
🍽️ Meal Tip: Vegetarian options near Arashiyama
