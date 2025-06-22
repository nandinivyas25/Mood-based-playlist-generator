```markdown
# 🎶 Mood-Based Playlist Generator 🎧

A creative Python project that recommends **music playlists** based on your **current mood** and **live weather** using the OpenWeather API.  
Because data doesn't have to be boring — it can have *soul* too. 💫

> Built with Python, creativity, and a love for data + music.

---

## 💡 Project Idea

Ever wondered what music fits your mood *and* the weather outside?

This app lets you input:
- Your **city** 🌍
- Your **mood** (happy, sad, relaxed, energetic) 😊

It then:
1. Fetches the **real-time weather**
2. Suggests a **custom playlist** that blends your mood and weather vibe

Perfect for days when you feel like the sky understands you. ☁️🎵

---

## 🛠️ Tech Stack

| Tool                | Use                            |
|---------------------|---------------------------------|
| Python              | Core programming language       |
| Jupyter Notebook    | Interactive development         |
| `requests`          | Weather API calls               |
| `dotenv`            | Environment variable handling   |
| OpenWeatherMap API  | Real-time weather information   |
| Spotify             | Hindi playlist curation         |

---

## 🔐 Step-by-Step Setup

### ✅ Step 1: Clone the repo
```bash
git clone https://github.com/yourusername/Mood-Based-Playlist-Generator.git
cd Mood-Based-Playlist-Generator
```

### ✅ Step 2: Install dependencies
```bash
pip install requests python-dotenv
```

### ✅ Step 3: Get your API key
- Visit [OpenWeatherMap](https://home.openweathermap.org/api_keys)
- Sign up → Go to API Keys → Copy your key

### ✅ Step 4: Create your `api_key.env` file
```env
API_KEY=your_openweather_api_key_here
```

> 🔐 **Make sure this file is in your `.gitignore` before uploading!**

---

## 🚫 How to Hide API Key (IMPORTANT)

1. Create a `.gitignore` file in the root folder of your project.
2. Paste this inside:
```bash
api_key.env
.env
__pycache__/
.ipynb_checkpoints/
*.pyc
```

3. If you already added the API key by mistake:
```bash
git rm --cached api_key.env
git commit -m "Removed API key"
```

---

## ▶️ How It Works

Run the notebook and enter your inputs:

```python
📍 Enter your city: kota
😊 How are you feeling? happy
🌤️ Current weather in Kota: Clear
🎧 Recommended Playlist:
https://open.spotify.com/playlist/4P6vJmjvZINgtrP4eTRXeN
```

---

## 💖 Example Output

```
📍 Enter your city: delhi
😊 How are you feeling? sad
🌧️ Current weather in Delhi: Rainy
🎧 Recommended Playlist:
https://open.spotify.com/playlist/1B7xy9V7vovkGkXx1g3CTd
```

---

## 🧠 Sample Mood-Weather Logic

| Mood      | Weather   | Playlist Theme                |
|-----------|-----------|-------------------------------|
| Happy     | Clear     | Dancey Bollywood/Indie Vibes  |
| Sad       | Rainy     | Soft Hindi + Lo-fi            |
| Energetic | Cloudy    | Hindi Hip-Hop, Beats          |
| Relaxed   | Windy     | Calm, acoustic songs          |

---

## 🌈 Behind the Scenes

This project was born from a simple question:

> *Can data science feel artistic, emotional, human?*

Turns out — yes it can. With weather + mood + music, we built a bridge between logic and emotion.  
This isn’t just about automation — it’s about expression.

---

## 🔗 Tags

`#PythonProjects` `#DataMeetsDesign` `#MoodTech`  
`#SpotifyDev` `#WomenInTech` `#CreativeCoding`  
`#BuildInPublic` `#TechForGood` `#OpenWeatherAPI`

---

## ✨ Dream Add-Ons

- Emoji-based mood input 😄😢
- Add your own Spotify login & play songs directly 🎵
- Weekly emotion heatmap 🔥📊
- A voice-based mood tracker 🎙️

---

## 👩‍💻 Author

Made with 💛 by **[Nandini Vyas](www.linkedin.com/in/nandini-vyas-27b142368)**  
✨ Data Science Learner | Python Explorer | Building Cool Things

---

## 🤝 Contributions Welcome

Pull requests and forks are welcome — feel free to:
- Add more playlists
- Suggest new features
- Make this even more human ❤️
```
