# Aura  
*Personalized, voice-driven AI assistant with end-to-end command execution and advanced privacy.*

Aura is a cross-platform, federated-learning-enabled assistant that converts natural-language voice commands into safe, sandboxed CLI actions and API calls. Built by the TensionFlow team, Aura combines cutting-edge ASR, a customizable LLM pipeline, and live integrations to help you automate complex tasks while keeping your data private.

---

## 🚀 Features

- **Personalized Assistant**  
  Custom fine-tuned LLM per user, adapting over time for more accurate, context-aware responses.

- **Improved Speech Recognition**  
  • Noise-cancellation + multi-mic fusion  
  • Tri-gram language model boosts accuracy by ~7.2% (from 85.6% baseline)

- **Natural Language → Command Generation**  
  Turn free-form requests into shell commands, e.g.  


- **High-Level & Refined Execution**  
• Scaffold and run boilerplate code (e.g., “create and run a basic React app”)  
• Automatic retry/refinement when commands fail

- **Complex Task Orchestration**  
• CRUD with Google Calendar  
• WhatsApp messaging  
• Email reading & scheduling  
• Web search and result ranking  
• Spotify playback by mood/genre  
• Live news, weather, and sports by location

- **Mathematical Equation Solving**  
Fast, step-by-step solver via AutoGen—outperforms standard MAmmoTH.

- **Privacy & Security**  
• Two-stage verification: login/signup + voice biometric  
• On-device content redaction before federated updates  
• Federated ML: central model fine-tuning on anonymized inferences

- **Live API Integrations**  
Plug-and-play connectors: Google, WhatsApp, Spotify, news/weather/sports, and more.

---

## ⚙️ Architecture Overview

1. **Audio Capture & ASR**  
 Multi-mic noise cancellation → enhanced speech recognition  
2. **Intent & Entity Extraction**  
 Custom NLU pipeline identifies actions, parameters, and context  
3. **Command Synthesis & Refinement**  
 LLM generates shell/API commands; sandboxed execution with auto-retry  
4. **Federated Feedback Loop**  
 Redacted transcripts → central LLM updates without exposing raw user data  
5. **Result Delivery**  
 Voice or text responses; optional logging/visual UI  

---

## 🛠 Installation

> **Requirements:**  
> – Python 3.10+  
> – Docker (for sandboxed CLI)  
> – AWS/GCP credentials (optional, for cloud integrations)


## 🔐 Security & Privacy

- Two-Factor Voice Biometric
- Content Redaction before any cloud upload
- Federated Learning ensures personal data never leaves your device unredacted

## 💸 Cost & Business Model

- Operational Cost: ~$100/month
- Breakeven Point: ~6 active users
- Pricing Strategy: Competitive SaaS model at $20/user/month

## 📈 Future Work

- Wake-word (“Hey Aura”) detection
- Third-party integrations: Zomato, Swiggy, Zoom, etc.
- Mobile SDK for iOS/Android

## 🙋‍♂️ Authors & Acknowledgments

TensionFlow Team
- Abhay Mathur
- Shreya Shah
- Aasmi Thadhani
- Aditya Shah

Thanks to the Codeshastra X hackathon for inspiration!
