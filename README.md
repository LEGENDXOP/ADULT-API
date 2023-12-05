
## 🚨 Adult Content Warning: 18+ Only 🚨

**Important Notice:** This repository contains material specifically designed for adults (18+). Viewer discretion is strongly advised.

---

### 🌟 Introduction

Hello Tech Enthusiasts!

As of now, this API is not open-source, but we are open to the idea of making it so, depending on the community response. To support this project:

- **Please star this repository! 🌟**
- **Send your valuable feedback on Telegram ([@LEGENDX22](https://legendx.co))**

---

### 🛠 Requirements

- **OpenAI API Key**: We recommend using a free key, as it works splendidly.

**Quick Insight:** This project integrates OpenAI partially, mainly for enhancing command understanding.

---

### 📡 API and Endpoints

To access the API and understand its endpoints, here's what you need:

- **Home Endpoint**: `https://adult-api-7a95944102ff.herokuapp.com`
- **Main (AI) Endpoint**: `https://adult-api-7a95944102ff.herokuapp.com/response`

---

### ⚙️ Parameters

- `api`: Your OpenAI API key (opt for free, but premium works too)
- `user_id`: A unique ID to keep track of each user's message history
- `message`: Your query for the adult AI
- `name`: (Optional) Your bot's name (or nickname) to personalize the AI's response
- `context`: (Optional) A list of strings to provide additional context to the AI (I prefer to not use this)
---

### 📚 Example

First install a module for making request i prefer u to use 'requests' module

`pip install requests`

```python
import requests

api = "https://adult-api-7a95944102ff.herokuapp.com/response"

response = requests.post(api, json={
    "api_key": "sk-xxxxf",
    "user_id": "legendx",
    "message": "Hello Baby How Are You..."
})

print(response.json())
```

---

### 📝 Tips

- To avoid conflicts, personalize your `user_id` by appending your name (e.g., `user_id=f"{yourname}-{userID}"`).

---

### 💬 Feedback

Your feedback is crucial for the growth of this project! Reach out to me on Telegram to share your thoughts and suggestions.

**Telegram: [@LEGENDX22](https://legendx.co)**

Thank you for exploring and supporting this project!
