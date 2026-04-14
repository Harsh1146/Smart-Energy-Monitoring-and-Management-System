# Smart Energy Monitoring System
### KR Mangalam University — Pre-Final Year Project

**Faculty Mentor:** Dr. Swati  
**Team:** Arshia Goswami, Vineet Yadav, Aadya Saxena, Harsh Mehto, Harsh Chaudhary

---

## Deploy to Render (Free)

### Option 1 — GitHub + Render (Recommended)

1. Create a new GitHub repository
2. Upload all files (keep the folder structure)
3. Go to [render.com](https://render.com) → Sign up free
4. Click **"New +"** → **"Web Service"**
5. Connect your GitHub repo
6. Render auto-detects `render.yaml` — click **Deploy**
7. Your site is live at `https://smart-energy-monitor.onrender.com`

### Option 2 — Manual Render Setup

1. Push code to GitHub
2. Render → New Web Service → Connect repo
3. Set:
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`
   - **Environment:** Node
4. Click Deploy

---

## Local Development

```bash
npm install
npm start
# Open http://localhost:3000
```

## Project Stack
- **Hardware:** NodeMCU ESP8266, PZEM-004T, Relay Module, CT Clamp
- **Firmware:** C++ / Arduino IDE
- **Cloud:** Blynk IoT
- **Website:** Node.js + Express (static serving)
