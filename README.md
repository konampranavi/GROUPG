# SafeAI: Intelligent Women’s Safety Agent

## 📝 Project Statement
**SafeAI** is an intelligent agent for women’s safety that proactively monitors a user’s environment using AI and ML. It assesses risk in real-time, interacts with the user via an AI assistant, and automatically alerts emergency contacts with live location if the user is unresponsive. SafeAI ensures smarter, proactive protection beyond traditional SOS apps.

---

## 💡 Problem Statement
Women’s safety remains a serious concern, and current apps mostly rely on **manual SOS triggers** that may fail during emergencies.  
There is a need for an **AI-driven solution** that can:

- Detect potentially unsafe situations proactively  
- Communicate with the user to verify risk  
- Automatically trigger help if required  

---

## 🚀 Proposed Solution
**SafeAI** is an intelligent safety companion that:

- Uses the **Browser Geolocation API** to access live location.  
- Runs a lightweight **ML model** to classify areas as “safe” or “unsafe”.  
- Uses **OpenAI LLM** to interact with the user:  
  _“You’ve entered a risky area. Should I start tracking you?”_  
- Tracks the user every 5 / 10 / 15 minutes (user-defined).  
- If no response after 3 alerts → sends **SMS/email** with live location to emergency contacts.  

---

## 🌟 Key Features
- **Proactive Safety Detection:** Identifies risky areas before emergencies occur.  
- **Intelligent Agent Interaction:** Uses AI to communicate and confirm the user’s status.  
- **Automated Alerts:** Sends location-based alerts if the user is unresponsive.  
- **Customizable Tracking:** User can define the tracking interval.  
- **Multi-channel Notifications:** SMS and email support for emergencies.  

---

## 🧠 Tech Stack
| Component | Technology |
|------------|-------------|
| Frontend / Hosting | Next.js + Vercel |
| AI / LLM | OpenAI GPT API |
| ML | Python (Scikit-learn) |
| Agent Logic | LangChain |
| Alerts | Twilio / EmailJS |
| Location & Voice | Browser Geolocation & Web Speech API |

---

## ⚙️ System Flow
1. User opens the app → grants location permission  
2. System checks area safety via ML model  
3. LLM interacts and monitors response  
4. No response → emergency alert sent to predefined contacts with location  

---

## 📈 Future Enhancements
- Real-time crime data integration  
- Multilingual AI voice assistant  
- Background tracking on mobile devices  
- Mobile app integration for offline functionality  

---

## 🎬 Demo / Screenshots
_Add screenshots or demo GIFs of your app here to impress the judges!_  

---

## 🧩 Hackathon Deliverables
- Updated `README.md` ✅  
- `requirements.txt`  
- Working code / notebook  
- 10-min demo video link  
