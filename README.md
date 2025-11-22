# 📱 WhatsApp AI Customer Support & Order Automation

This project is a fully automated system that allows customers to communicate through WhatsApp and:

- ✔ Ask questions about products  
- ✔ Receive instant answers from an AI agent  
- ✔ Place orders directly through chat  
- ✔ Automatically save order details into Google Sheets  

It is designed for businesses that want fast, hands-free customer service and order management without needing a website or mobile app.

---

## 🎬 Demo Video

🎥 **Watch Demo:**  
[![Watch the Demo](asset/Thumbnail.jpg)](https://vimeo.com/1139488072)  
*Click the image above to watch the real-time Customer Support & Order demo.*

---

## 🌟 How It Works (Simple Explanation)

1. Customer sends a message on WhatsApp  
2. The AI reads the message and understands the request  
3. It looks up:
   - Product information  
   - FAQs  
   - Pricing  
4. The AI sends a helpful reply back  
5. If the customer wants to place an order:
   - The AI collects the order details  
   - Saves them into Google Sheets  
   - Confirms the order to the customer  

Everything runs automatically — no manual involvement needed.

---

## 🧠 What the AI Can Do

### 💬 Answer Product Questions
- Product features  
- Descriptions  
- Pricing  
- Frequently asked questions  

### 🛒 Take Orders
- Collect product name and quantity  
- Save order details to Google Sheets  
- Provide instant confirmation  

### 🧠 Maintain Conversation Context
- The AI remembers the ongoing chat
- Responses feel natural and human-like  

---

## ⚙️ Technology Used

| Purpose | Tool |
|---|---|
| Messaging Platform | WhatsApp |
| AI Brain | Google Gemini Chat Model |
| Memory | Session-based memory |
| Product Information | Google Docs |
| Pricing Data | Google Sheets |
| Order Storage | Google Sheets |
| Automation | N8N (or any workflow automation tool) |

---

## 📊 Order Sheet Structure

Orders are saved in a spreadsheet with fields like:

| Column | Meaning |
|---|---|
| Customer Name | Person placing the order |
| Product | Item ordered |
| Quantity | Units ordered |
| Price | Pulled from pricing sheet |
| Timestamp | When the order was placed |

---

## 🔁 Workflow Overview

WhatsApp → AI Agent → Google Docs + Sheets → WhatsApp Response

The AI connects to:

- Product FAQs  
- Product descriptions  
- Pricing sheet  
- Order sheet  

This helps it answer customer questions and store orders automatically.

---

## 🚀 Who Is This For?

This system is ideal for:

- Small businesses  
- Online sellers  
- Home entrepreneurs  
- Retail shops  
- Anyone who receives customer messages on WhatsApp  

Once set up, no technical skills are needed to operate it.

---

## 💡 Benefits

- Saves time  
- Fully automated  
- Reduces manual errors  
- Provides fast customer responses  
- Keeps all orders stored and organized  

---

---

## 🛠 Setup (High-Level)

1. Configure WhatsApp Business API  
2. Set up an automation tool (like N8N)  
3. Connect:
   - Google Docs for product details  
   - Google Sheets for pricing and orders  
4. Add Google Gemini as the AI engine  
5. Deploy and test with real WhatsApp messages  

---

## 📄 License

This project is released under the **MIT License**.

