# Mychatboat
Imagination sydney 
# 🤖 Imagination Sydney AI Chatbot

An AI-powered chatbot for **Imagination Sydney** that answers every visitor's questions instantly — about the business, its services, and more — 24/7.

Built with the **Grok API** and developed on **Replit**.
<img width="447" height="447" alt="sydney" src="https://github.com/user-attachments/assets/04de08b9-fead-46a2-b104-970bbfe00928" />

## ✨ Features

- 💬 Instant answers to visitor questions, anytime
- 🧠 Powered by Grok (xAI) for natural, helpful conversations
- 🏢 Trained with Imagination Sydney's business details (services, contact info, FAQs)
- 📱 Clean, responsive chat interface (works on mobile & desktop)
- ⚡ Fast setup and easy deployment

---

## 🛠️ Tech Stack

| Part | Technology |
|------|------------|
| AI Model | Grok API (xAI) |
| Development | Replit |
| Hosting | Vercel / Replit |
| Frontend | HTML, CSS, JavaScript *(update if different)* |
| Backend | Node.js / Python *(update if different)* |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Install dependencies

```bash
npm install
```
*(or `pip install -r requirements.txt` if using Python)*

### 3. Add your API key


Create a `.env` file in the root folder:

```env
GROK_API_KEY=your_grok_api_key_here
```

> ⚠️ Never share your API key publicly or commit the `.env` file to GitHub. On Replit, use the **Secrets** tab instead.

### 4. Run the project

```bash
npm start
```

Then open the local URL shown in the terminal.

---

## ☁️ Deployment

**On Replit:** Click the **Deploy** button in your Repl and follow the steps.

**On Vercel:**
1. Push the project to GitHub
2. Import the repo on [vercel.com](https://vercel.com)
3. Add `GROK_API_KEY` under *Environment Variables*
4. Click **Deploy**

---

## 📂 Project Structure

```
├── index.html        # Chat interface
├── style.css         # Styling
├── script.js         # Frontend logic
├── server.js         # Backend / API calls
├── .env              # API key (not committed)
└── README.md         # Project documentation
```
*(Update this to match your actual files.)*

---

## 🧩 Customization

To teach the chatbot about the business, edit the **system prompt** (in `server.js` or the config file) and include:

- Business name, services and pricing
- Contact details and location
- Opening hours
- Frequently asked questions
- Tone of voice (friendly, professional, etc.)

---

## 🗺️ Roadmap

- [ ] Add chat history
- [ ] Multi-language support
- [ ] Lead capture (name / email / phone)
- [ ] Admin dashboard for updating business info

---

## 🤝 Contributing

Suggestions and improvements are welcome! Fork the repo, make your changes, and open a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

**Manpreet Sirohi**
📸 Instagram: [@manpreet_sirohi_23](https://instagram.com/manpreet_sirohi_23)

---

⭐ If you like this project, give it a star on GitHub!

