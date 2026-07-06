# AI Support Chatbot — E-commerce Order Tracking & Booking Automation

A functional, embeddable AI-style customer support chatbot built for e-commerce and small business websites. Demonstrates automated handling of order tracking, appointment booking, return/refund queries, and human handoff — the exact workflows that drain support-team hours on real client sites.

**[▶ Live Demo](#)** &nbsp;|&nbsp; **[🎥 Video Walkthrough](#)**

*(Replace the links above with your GitHub Pages URL and video link once hosted.)*

---

## Why This Exists

Small e-commerce and service businesses answer the same 5–6 questions all day — "where's my order," "can I book a slot," "what's your return policy." This project shows how that entire first layer of support can be automated, freeing the business owner or team to handle only the conversations that actually need a human.

This demo was built end-to-end — conversation design, UI, and front-end logic — as a self-contained example of the kind of chatbot I build for freelance clients.

---

## Features

- 🛒 **Order Tracking** — captures an order number and returns a contextual shipping status
- 📅 **Appointment Booking** — collects preferred date/time and confirms the booking
- ↩️ **Return & Refund Handling** — answers policy questions inline
- 🙋 **Smart Human Handoff** — recognizes when a query needs a real agent and escalates gracefully
- 💬 **Quick-Reply UI** — guided buttons alongside free-text input, reducing friction for the user
- ⚡ **Typing Indicator & Realistic Response Timing** — mimics a natural conversational feel

## Tech Stack

- **HTML5 / CSS3** — custom design system (no framework dependency)
- **Vanilla JavaScript** — conversation state machine, keyword-based intent matching
- **Google Fonts** (Fraunces, IBM Plex Sans) for typography

No build step required — it's a single self-contained HTML file.

---

## Architecture Note — Read Before Assuming This Is LLM-Powered

This demo runs on a **rule-based conversational engine** (keyword/intent matching with scripted response logic), *not* a live large language model. It was built this way intentionally, to demonstrate conversation design and automation logic in a fast, dependency-free, cost-free package.

In production client work, this same interaction design is the blueprint I extend with a real LLM backend — typically via the **OpenAI API** or **Claude API** — for dynamic, open-ended conversations, plus integrations like **Zapier/Make** for connecting to a business's actual order/booking systems.

If you're evaluating this for a real project: what you see here is the *interaction design and automation logic*. The production version adds a language model on top of this same structure.

---

## Run It Locally

No dependencies, no build tools — just open the file.

```bash
git clone https://github.com/<your-username>/ai-chatbot-demo.git
cd ai-chatbot-demo
open index.html   # or double-click the file, or use a local server:
python3 -m http.server 8000
```

Then visit `http://localhost:8000` if using a local server.

---

## What I'd Build Next (Production Roadmap)

- [ ] Swap rule-based engine for OpenAI/Claude API for open-ended conversation handling
- [ ] Connect to a real order-management system (Shopify/WooCommerce API) for live order status
- [ ] Add calendar integration (Google Calendar / Calendly API) for real booking confirmation
- [ ] Persist conversation history per user session
- [ ] Add analytics to track deflection rate (support tickets avoided)

---

## About Me

I build AI-assisted web solutions for small businesses — WordPress fixes, custom chatbots, and workflow automation using Zapier/Make and LLM APIs.

- 🔗 Upwork: [Your Upwork profile link]
- 📧 Contact: [Your email/contact link]

If you're a business owner looking to automate repetitive support work like the flow shown above, feel free to reach out.
