📱 WhatsApp AI Customer Support & Order Automation

This project is a fully automated system that allows customers to communicate through WhatsApp and:

✔ Ask questions about products
✔ Receive instant answers from an AI agent
✔ Place orders directly through chat
✔ Automatically save order details into Google Sheets

It is designed for businesses that want fast, hands-free customer service and order management without needing a website or mobile app.

🎥 Demo Video

▶ Watch the demo:
[https://drive.google.com/file/d/1nB7O_LXTegyI-FoaLDQ5REtf5Ukrg1aF/view?usp=sharing](https://vimeo.com/1139488072?fl=ip&fe=ec)

🌟 How It Works (Simple Explanation)

1️⃣ Customer sends a message on WhatsApp
2️⃣ The AI reads the message and understands the request
3️⃣ It looks up:

Product information

FAQs

Pricing
4️⃣ The AI sends a helpful reply back
5️⃣ If the customer wants to place an order:

AI collects the details

Saves the order to Google Sheets

Confirms back to the customer

Everything runs automatically — no manual involvement needed.

🧠 What the AI Can Do
💬 Answer Product Questions

Product features

Descriptions

Pricing

Frequently asked questions

🛒 Take Orders

Collect product and quantity

Store order in Google Sheets

Provide confirmation instantly

🧠 Remember Conversation

The AI keeps track of chat context so responses feel natural and human-like.

⚙️ Technology Used
Purpose	Tool
Messaging Platform	WhatsApp
AI Brain	Google Gemini Chat Model
Memory	Simple session-based memory
Product Data	Google Docs
Pricing	Google Sheets
Order Storage	Google Sheets
Automation	N8N (or any workflow automation tool)
📊 Order Sheet Structure

Orders are saved in a spreadsheet with fields such as:

Column	Meaning
Customer Name	Person placing the order
Product	Item ordered
Quantity	Number of units
Price	Pulled from pricing sheet
Timestamp	When the order was placed
🔁 Workflow Overview
WhatsApp → AI Agent → Google Docs + Sheets → WhatsApp Response


The AI is connected to:

Product FAQs

Product descriptions

Pricing sheet

Order sheet

This enables it to understand questions and store orders automatically.

🚀 Who Is This For?

This system is ideal for:

Small businesses

Online sellers

Home businesses

Retail stores

Anyone receiving customer messages on WhatsApp

Once set up, no technical skills are required to use it.

💡 Benefits

Saves time

Fully automated

Reduces mistakes

Delivers fast customer replies

Keeps orders organized in one place

📸 System Screenshot

(Replace with your own screenshot path if needed)

🛠 Setup (High-Level)

Configure WhatsApp Business API

Set up automation tool (e.g., N8N)

Connect:

Google Docs for product info

Google Sheets for pricing & orders

Add Google Gemini AI as the chatbot engine

Deploy and test using a real WhatsApp message

📄 License

This project is provided under the MIT License.
