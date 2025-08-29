# 🚀 NASA Astronomy Picture of the Day (APOD) Viewer

This project is a simple web app that uses **NASA's Astronomy Picture of the Day API**.  
It allows users to:

- View the **current image of the day** when the page loads.
- Search for APOD images by **selecting a date**.
- Save searched dates to **localStorage**.
- Display and re-use **search history** with clickable dates.


---

## ⚡ Features

- **Current Image of the Day** shown automatically on page load.
- **Search by Date** using a date picker.
- **Local Storage Support** for saving past searches.
- **Search History** list with clickable dates to reload past results.
- Supports both **images** and **videos** (some APOD results are YouTube embeds).
- **Error Handling** for invalid requests or API issues.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
- **NASA APOD API**

---

## 🔑 Getting Started

### 1. Clone the Repository

git clone https://github.com/khedkar2001/Nasa-images.git
cd Nasa-images

### 2. Get a NASA API Key

Go to https://api.nasa.gov/

Sign up with your email to generate a free API key.

Replace DEMO_KEY in script.js with your personal key:

const apiKey = "YOUR_API_KEY_HERE";

### 3. Run Locally

Just open index.html in your browser (no server required).


🎯 Checklist

 HTML Structure: Form, input, submit button, result container, and history list.

 CSS Styling: Responsive, dark-theme style, visually appealing.

 getCurrentImageOfTheDay(): Fetch & show today’s APOD.

 getImageOfTheDay(): Fetch & show searched date APOD.

 saveSearch(): Store searches in localStorage.

 addSearchToHistory(): Display and handle clickable search history.

 Error Handling: Handles failed requests.

 Deployment: Repo + live working link.

---
👨‍💻 Author

Saurabh Khedkar 

Full Stack Web Developer | Pune, MH, India 

📧 saurabhrkhedkar1707@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/saurabh-khedkar)  
🐙 [GitHub](https://github.com/khedkar2001)  

