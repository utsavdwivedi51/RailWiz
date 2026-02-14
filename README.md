# RailWiz - AI‑Powered Railway Assistant (Demo)

RailWiz is a **conceptual prototype** of an intelligent railway ticketing website that goes beyond traditional booking apps. It combines a clean, modern UI with an AI‑driven layer to offer predictive insights, natural language interaction, and proactive journey management – all in one place.

This repository contains a **fully interactive front‑end demo** built with HTML, CSS, and JavaScript. It simulates core features like smart train search, PNR status, live tracking, and a conversational AI chatbot named **Riya**.

---

## Key Features

- **Personalised AI Greeting** – Adapts to time of day and shows your upcoming trip.
- **Intelligent Train Search** – Search trains with natural language; results include AI tags (e.g., confirmation probability, on‑time performance).
- **PNR Status with Prediction** – Enter a 10‑digit PNR to see current status plus an AI‑generated likelihood of confirmation.
- **Live Train Tracking** – Real‑time location and delay estimates (mock data).
- **AI Chatbot "Riya"** – Conversational assistant that can handle booking, PNR inquiries, and general travel questions.
- **Dark Mode Toggle** – Seamless switch between light and dark themes.
- **Responsive Design** – Works on desktop, tablet, and mobile.
- **Micro‑interactions** – Smooth hover effects, animations, and a floating chat bubble.

All data is **mocked** to demonstrate the look and feel. The interactions are designed to showcase how AI can enhance every step of the railway travel experience.

---

## Demo

You can run the demo instantly by opening the `index.html` file in any modern browser.  
No build tools or servers required.

---

## How to Use

1. **Clone or download** this repository.
2. Open `index.html` in your browser.
3. Explore the features:
   - Click **Book Ticket**, **PNR Status**, **Live Train** quick actions.
   - Use the search, PNR, and live train cards – they respond with mock results.
   - Click the **chat bubble** or the **Chat with Riya** button to open the AI assistant.
   - Toggle dark mode using the moon/sun icon in the header.

### Sample Chat Queries
Try typing these in the chatbot:
- "Hi"
- "Book a ticket to Delhi"
- "Check PNR 1234567890"
- "Is my train late?"
- "Thank you"

---

## Technologies Used

- **HTML5** – structure
- **CSS3** – styling, animations, dark mode, responsive grid
- **JavaScript (ES6)** – interactivity, chat logic, mock data updates
- **Font Awesome 6** – icons for visual appeal
- **Google Fonts (Inter)** – clean typography

No external frameworks or libraries – pure vanilla code for easy understanding and modification.

---

## Project Structure

```
railwiz-demo/
│
├── index.html          # Main HTML file (includes all CSS & JS)
└── README.md           # This file
```

Everything is self‑contained in a single HTML file. You can inspect, modify, or extend it as you wish.

---

## Future Enhancements

While this is a front‑only prototype, a production version of RailWiz would include:

- **Backend integration** with real Indian Railways APIs (e.g., IRCTC, RailYatri).
- **Machine learning models** for delay prediction, waitlist movement, and personalisation.
- **Full conversational booking** using a fine‑tuned LLM.
- **User authentication** and travel history.
- **Crowdsourced insights** (platform crowds, food quality) validated by AI.
- **Multi‑modal suggestions** (cabs, buses) integrated into the journey view.

---

## License

This project is open‑source and available under the [MIT License](LICENSE). Feel free to use it as a starting point for your own ideas.

---

## Acknowledgements

Inspired by platforms like ConfirmTkt, Ixigo, and the vision of AI‑first travel assistants.  
Made with ❤️ for a smarter railway experience.

---

*For any questions or suggestions, feel free to reach out or open an issue.*
