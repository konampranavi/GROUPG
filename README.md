# SafeAI: Intelligent Women’s Safety Agent

---

## 📝 Project Statement
**SafeAI** is an intelligent, privacy-first women’s safety agent designed to give users confidence and control while traveling alone. Women often feel unsafe due to the lack of instant, reliable ways to share location, assess route safety, and get help during emergencies. SafeAI addresses this gap by combining **real-time location sharing, predictive route safety, and low-friction emergency support** in a single app.  

**Key differentiators include:**  
- **Privacy-first, time-limited location sharing** — no always-on tracking; users control who sees their location and for how long.  
- **Predictive safety** — risk scoring for routes using contextual data like lighting, foot traffic, and historical incidents.  
- **Low-friction emergency escalation** — single-tap SOS triggers alerts with live location, audio/video capture, and optional automatic calls to trusted contacts and emergency services.  
- **Community-sourced safe spots** — verified businesses, transit stations, and public areas where users can seek refuge.  
- **Accessibility & seamless UX** — voice activation, wearable support, and intuitive interface reduce friction in stressful situations.  

**MVP (Minimum Viable Product):**  
1. Account creation with trusted contacts.  
2. Time-limited live location sharing.  
3. One-tap SOS with location, path, and optional media capture.  
4. Geofenced arrival notifications.  
5. Transparent, consent-driven privacy and basic encryption in transit.  

SafeAI empowers women to travel safely while retaining control of their personal data.  

---

## 💡 Problem Statement
Women’s safety remains a serious concern, and current apps mostly rely on **manual SOS triggers** that may fail during emergencies. There is a need for a **privacy-first AI-driven solution** that can:  

- Detect potentially unsafe situations proactively  
- Communicate with the user to verify risk  
- Automatically trigger help if required  

---

## 🚀 Proposed Solution
**SafeAI** is an intelligent safety companion that:  

- Uses **Browser Geolocation API** for live location tracking  
- Runs a lightweight **ML model** to classify areas as “safe” or “unsafe”  
- Interacts via **OpenAI GPT / LangChain** to guide and alert the user  
- Tracks user location every 5 / 10 / 15 minutes (user-defined)  
- Sends **SMS/email alerts with location and media** if user is unresponsive  

---

## 🌟 Core Features
- **Quick SOS / Panic Button**: single-tap alerts with location and optional media.  
- **Time-limited Live Location Share**: share for a defined period with one or multiple contacts.  
- **Safe-route Recommendations**: prioritize well-lit, high-traffic routes.  
- **Geofenced Check-ins & Arrivals**: auto-notify trusted contacts on destination arrival.  
- **Trusted Circle & Consent Controls**: explicit opt-in, revoke access anytime.  
- **Community Safe Places / Vetted Hubs**: verified nearby safe spots.  
- **Incident Capture**: audio/video + map snapshot on SOS trigger.  
- **Low-data / Low-battery Mode**: efficient location tracking.  
- **Anonymous Incident Reporting**: report unsafe spots without revealing identity.  

**Innovative Add-ons:**  
- Predictive Risk Score based on time, lighting, foot traffic, historical incidents  
- AI anomaly detection (e.g., sudden stop, phone discarded)  
- Ride/transit integration for monitoring  
- Check-in if late automation  
- Privacy-first social proof: density estimates without revealing identities  

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
| Backend | Node.js / Express or Firebase Cloud Functions |
| Storage | Firebase Storage / AWS S3 |
| Auth | Firebase Auth with 2FA |

---

## ⚙️ System Flow
1. User opens app → grants location permission  
2. System checks area safety via ML model  
3. LLM interacts and monitors response  
4. No response → emergency alert sent to predefined contacts  
5. Emergency contact receives alert with **location, path, and optional media**  

---

## 📊 Block Diagram
> <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a329362f-8b2e-4563-a42b-766dd6bf30da" />
  
> *Visual representation of SafeAI system flow including Location API → ML Risk Model → LLM Interaction → Emergency Alert.*  

*(Replace `path/to/block-diagram.png` with your uploaded diagram in the repo.)*

---

## 🔐 Privacy & Legal Considerations
- **Explicit, granular opt-in** for location sharing  
- **Time-limited access** with auto-expiry  
- **Data minimization**: store only what’s necessary for short durations  
- **End-to-end encryption** for alerts and sensitive media  
- **Anti-abuse protections**: rate limits, abuse reporting, consent logs  
- Comply with local laws and emergency service protocols  

---

## 📈 Future Enhancements
- Real-time crime data integration  
- Multilingual AI voice assistant  
- Mobile background tracking  
- Verified safe spots network  
- Ride monitoring integration  
- Advanced anomaly detection  

---

## 🎬 Demo / Screenshots
_Add screenshots, GIFs, or demo video links here to impress the judges!_  

---

## 🧩 Hackathon Deliverables
- Updated `README.md` ✅  
- `requirements.txt`  
- Working code / notebook  
- 10-min demo video link  
