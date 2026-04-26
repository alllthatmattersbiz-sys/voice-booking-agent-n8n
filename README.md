# 🎤 Voice Booking Agent with n8n

An automated hotel reservation system that:
1. Receives voice calls via **Vapi**
2. Orchestrates workflow with **n8n**
3. Creates Google Calendar events
4. Sends confirmation emails

## 🏗️ Architecture
Vapi (Voice Call)
↓
n8n (Workflow Orchestration)
├─ Function Node (Parse booking data)
├─ Google Calendar (Create event)
└─ Gmail (Send confirmation)

## ⚡ How It Works

1. **Call** the Vapi phone number
2. **Book** a hotel room (AI asks for details)
3. **Automatically:**
   - Calendar event created
   - Confirmation email sent

## 🚀 Tech Stack

- **Vapi** - AI voice agent
- **n8n** - Workflow automation
- **Google Calendar API** - Event creation
- **Gmail API** - Email confirmations
- **JavaScript** - Data parsing

## 📦 Setup

1. Clone this repo
2. In n8n.cloud, create new workflow
3. Import `workflow.json`
4. Add your credentials:
   - Vapi API key
   - Google Calendar OAuth
   - Gmail OAuth
5. Deploy!

## 💰 Cost

- Vapi: ~$0.10 per call
- n8n.cloud: Free tier
- Google APIs: Free
- Gmail: Free

**Total cost per booking: ~$0.10**

## 🎯 Demo

[Link to demo video once recorded]

## 📝 What I Learned

- n8n is powerful for API orchestration
- Voice + automation = strong business value
- Vapi transcription quality is impressive
- Dynamic data parsing in workflows

## 🔄 Future Features

- [ ] SMS confirmations
- [ ] Multi-language support
- [ ] Slack notifications
- [ ] Payment integration
- [ ] Calendar availability checking

---

**Production-ready voice booking automation**
