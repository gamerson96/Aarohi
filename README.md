# Aarohi
Aarohi – Where Life Rises
Aarohi is a voice-powered, AI-inspired blood donor matching platform designed to support Thalassemia patients and other chronic transfusion needs. Built as a highly polished, mobile-first web application using HTML, Tailwind CSS, and vanilla JavaScript, Aarohi allows patients to raise urgent blood requests, track their status in real time, and connect with nearby donors—all from the palm of their hand.

## 🔗 Live Demo  
👉 [Click here to try Aarohi live](https://aarohi-chi.vercel.app/)


Every aspect of Aarohi’s user interface has been crafted for clarity and compassion. A patient dashboard makes it easy to submit a new request by specifying blood type, units needed, location, and urgency, while a donor dashboard lets volunteers toggle their availability, view nearby requests, and track the number of lives they’ve saved. Once a request is raised, an animated timeline and embedded map display each stage—Request Raised, Donor Matched, and Donor En Route—complete with a smoothly moving marker that simulates a donor’s approach to the hospital.

At the heart of Aarohi is an interactive voice assistant. Patients may tap the microphone to speak their needs or switch to keyboard input; a chatbox then appears with conversational messages from “Aarohi” offering guidance and next steps. A small, floating avatar keeps the experience friendly and reassuring, while a loader animation and a mock API integration (using JSONPlaceholder) simulate real-world data fetching so that every interaction feels robust and production-ready.

Behind the scenes, Aarohi is structured for easy extension into a full-stack solution. We plan to integrate a Node.js and MongoDB backend that will handle secure patient and donor authentication, hospital inventory synchronization, and real WhatsApp/SMS alerts via Twilio or the WhatsApp Cloud API. An AI layer (XGBoost and LSTM models) will forecast donor availability based on past donation history, regional patterns, and eligibility windows. Role-based access control will ensure that hospitals, NGOs, and verified volunteers can all participate safely, while rigorous data-privacy measures will protect sensitive health information in compliance with applicable regulations.

Aarohi’s roadmap also includes a donation analytics dashboard for Blood Warriors and partner organizations, multilingual support for wider accessibility, offline-capable functionality for low-connectivity areas, and progressive web app features to allow installation on any device. Our goal is not just to demonstrate a working prototype, but to lay the foundation for a scalable, life-saving platform that can be deployed across communities in need.

Getting Started
Clone this repository and open index.html in your browser to explore the current prototype. To deploy, push the code to GitHub and enable Pages in the repository settings, or import the project into Vercel for one-click hosting.

Contributing
We welcome feedback and contributions. If you would like to help enhance Aarohi—whether by refining the UI, building the backend services, or expanding its reach—please open an issue or submit a pull request. Together, we can bring this vision to life and ensure that no patient waits for a drop of hope.
