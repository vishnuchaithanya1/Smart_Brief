# 📖 SmartBrief — AI-Powered Article Summarizer 🚀  

**SmartBrief** is a modern full-stack web application that converts long articles into concise, easy-to-read summaries using **RapidAPI’s NLP engine**.  
With its clean UI, local history tracking, and clipboard support, it’s perfect for busy readers who want quick insights.  

---

## ✅ Features  

- 🔗 Paste any article URL to get a **brief AI-generated summary**  
- 📝 View and copy your past summaries (saved locally in browser)  
- 🎨 Minimal, responsive UI built with **React + Tailwind + Vite**  
- ⚡ Efficient state management with **Redux Toolkit (RTK Query)**  
- 🤖 Summarization powered by **RapidAPI (Article Extractor & Summarizer API)**  
- 📱 Works seamlessly on both **desktop and mobile**  

---

## 📦 Tech Stack  

| Layer            | Technologies                                  |
|------------------|-----------------------------------------------|
| **Frontend**     | React, Vite, Tailwind CSS                     |
| **State Mgmt.**  | Redux Toolkit (RTK Query)                     |
| **Summarization**| RapidAPI (Article Extractor & Summarizer API) |
| **Storage**      | Browser `localStorage` for summary history    |
| **Deployment**   | Vercel                                        |

---

## 🛠️ Installation & Setup  

### 1️⃣ Clone the repo  
```bash
git clone https://github.com/vishnuchaithanya1/Smart_Brief.git
cd Smart_Brief
```

### 2️⃣ Install dependencies  
```bash
npm install
```

### 3️⃣ Configure environment variables  
Create a `.env` file in the root directory and add your RapidAPI key:  
```env
VITE_RAPID_API_KEY=YOUR_RAPIDAPI_KEY_HERE
```
👉 [Get your API key from RapidAPI](https://rapidapi.com)  

### 4️⃣ Run the project  
```bash
npm run dev
```
App will be available at 👉 **http://localhost:5173**

---

## 💼 Usage  

1. Paste a valid article URL (e.g., BBC, NYT, The Verge).  
2. Press **Enter** or click **Submit**.  
3. Wait for the **loader animation**, then view your summary.  
4. Access history of past summaries.  
5. Click a summary card to **copy or revisit** it.  

---

## ⚙️ Configuration  

- ✂️ To adjust summary length → modify `length` parameter in `src/services/article.js`.  
- 🌗 Dark/Light mode → customize via `tailwind.config.js` or CSS variables.  

---



## 📂 Project Structure  

```
src/
├── assets/
├── components/      # Reusable UI components
├── services/        # RTK Query API slice
├── styles/          # Global styles + Tailwind overrides
├── App.jsx
├── main.jsx
.vite.config.js
.tailwind.config.js
.env
package.json
```

---

