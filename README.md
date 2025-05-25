# 🎬 Movie Recommendation System

Welcome to the **Movie Recommendation System** — an intelligent web application that helps users discover movies through traditional filtering and AI-powered conversations. This project is built using **Flask**, integrated with **Google's Gemini 1.5 Flash API** for conversational recommendations.

---

## 🚀 Features

### 1. 🔍 **Genre-Based Recommendations**
- Users can select a genre (e.g., Action, Comedy, Drama).
- Results can be filtered by:
  - ⭐ IMDb Rating (Highest to Lowest)
  - 📅 Year (Newest to Oldest, only movies up to year 2018)
- Pagination is supported for smooth browsing.

### 2. 🎞️ **Movie-to-Movie Recommendations**
- Get suggestions based on a movie you've already watched or liked.
- Similar movies are recommended using content-based filtering.
- You can also filter these recommendations by rating or year.

### 3. 🤖 **AI Movie Chat Assistant**
- Powered by **Gemini 1.5 Flash API** from Google AI.
- Ask questions like:
  - “Suggest me something funny to watch.”
  - “Recommend a thriller released before 2010.”
  - “Who directed Inception?”
- The chatbot understands mood-based queries and movie-related knowledge.

---

## 🧠 Technologies Used

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: Google Gemini 1.5 Flash (via `google-generativeai`)
- **Data**: CSV datasets (movies, ratings, tags)
- **Deployment**: Render, GitHub

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/movies-recommendation.git
cd movies-recommendation
