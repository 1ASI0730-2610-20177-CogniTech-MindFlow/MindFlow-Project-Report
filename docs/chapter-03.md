# Capítulo III: Requirements Specification

---

## 3.1. User Stories

---
| Epic ID | Epic Name | Descripción |
|---------|-----------|-------------|
| E1 | Identity, Privacy & Core Platform | Management of security, user authentication, and fundamental environment configuration. |
| E2 | AI-Powered Emotional Intelligence | Implementation of the AI core for sentiment analysis and empathetic feedback. |
| E3 | Smart Wellness & Habit Engineering | Logic for habit management and proactive intervention systems for stress. |
| E4 | Analytics, Monetization & Scalability | Data visualization module, business model, and system optimization. |

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|------------------------|--------------------------|
| US01 | OAuth Registration (Google) | As a new user, I want to register using my Google account, so that I can access the platform quickly. | Given the user is on the signup page, when they select "Continue with Google", then the system successfully creates the linked account. | E1 |
| US02 | Traditional Login | As a user, I want to log in with email and password, so that I have a manual entry alternative. | Given the user has an active account, when they enter valid credentials, then they are granted access to the dashboard. | E1 |
| US03 | Account Recovery | As a user, I want to reset my password via an email link, so that I don't lose my account if I forget it. | Given the user requests a reset, when they receive the email and update the password, then they can log in again. | E1 |
| US04 | PIN Lock | As a user, I want to set a security PIN, so that I can protect my privacy from unauthorized physical access. | Given the app is opened, when the PIN lock is active, then the system requests the code before showing any content. | E1 |
| US05 | User Profile | As a user, I want to edit my personal details (name, occupation), so that the AI can personalize its language with me. | Given the user is in settings, when they update their data, then the changes are reflected across the entire platform. | E1 |
| US06 | Dark Mode Interface | As a user, I want to enable dark mode, so that I can avoid eye strain during night use. | Given the user changes the theme in settings, when they confirm, then the entire UI darkens automatically. | E1 |
| US07 | Account Deletion | As a user, I want to delete my account and purge my records, so that I can exercise my right to total privacy. | Given the user requests deletion, when they confirm, then the system permanently removes all their data. | E1 |
| US08 (T) | AES-256 Encryption | As an architect, I want to implement encryption for journal entries in the DB, so that I can ensure total confidentiality. | Given sensitive text is saved, when it enters the database, then the content must be stored in an encrypted format. | E1 |
| US09 (T) | CI/CD Pipeline | As a developer, I want to configure an automated deployment flow, so that I can ensure fast and error-free deliveries. | Given a push is made to the main branch, when unit tests pass, then the code is automatically deployed to production. | E1 |
| US10 (T) | API Security (JWT) | As a developer, I want to implement JWT, so that I can secure backend requests and protect user data. | Given a user logs in, when they request data, then they must provide a valid token for the system to respond. | E1 |
| US11 | Journal Entry | As a student, I want to write free-text entries, so that I can vent my thoughts and feelings. | Given the user opens the editor, when they write and save, then the entry is linked to the current date. | E2 |
| US12 | Real-time Sentiment Analysis | As a user, I want the AI to analyze my text upon saving, so that I can receive a classification of my current mood. | Given the user saves a journal entry, when the NLP engine processes the text, then a sentiment label is displayed. | E2 |
| US13 | AI Empathetic Feedback | As a professional, I want to receive support from the AI after registering a mood, so that I feel immediate emotional validation. | Given a negative sentiment is detected, when processing the entry, then the AI displays a warm and empathetic message. | E2 |
| US14 | Contextual Tags | As a user, I want to categorize my entries (Work, Family), so that I can identify which area stresses me the most. | Given the user writes an entry, when they select a tag, then the monthly report is updated by category. | E2 |
| US15 | Multimedia Attachment | As a user, I want to upload photos to my entries, so that I can have a visual record of significant moments. | Given the user is in the journal, when they upload an image, then it is successfully associated with the saved entry. | E2 |
| US16 | Keyword Search | As a user, I want to search past entries by keywords, so that I can review specific life events. | Given a search term is entered, when the search is executed, then the system lists all matching entries. | E2 |
| US17 | Mood Calendar | As a user, I want to see a calendar with colors representing my mood, so that I can detect monthly emotional patterns. | Given the calendar view is opened, when there are records, then each day displays its dominant mood color. | E2 |
| US18 | Weekly AI Summary | As a user, I want to receive a mood summary every Sunday, so that I can reflect on my well-being throughout the week. | Given the week ends, when the user enters the app, then the AI generates a narrative summary of their week. | E2 |
| US19 (T) | LLM API Integration | As a developer, I want to connect the Gemini API, so that I can process natural language and generate empathetic responses. | Given text reaches the backend, when requested from the API, then the system receives a structured JSON response. | E2 |
| US20 (T) | Sentiment Logging | As a developer, I want to log AI response metrics, so that I can improve the accuracy of the NLP model over time. | Given the AI responds, when the process concludes, then the success metric is stored in the logs. | E2 |
| US21 | Create Habits | As a user, I want to define personalized goals, so that I can improve my daily self-care discipline. | Given the user is in the habits section, when they enter a name and frequency, then the habit is added to their checklist. | E3 |
| US22 | Completion Check | As a user, I want to mark habits as completed, so that I can visualize my daily progress in real-time. | Given a habit is fulfilled, when the user checks it off, then their discipline streak increases. | E3 |
| US23 | Stress-based Adjustment | As a professional with burnout, I want the app to reduce my workload if my mood is low, so that I don't feel overwhelmed. | Given the mood is "Very Negative", when habits are loaded, then the app suggests postponing heavy tasks. | E3 |
| US24 | Breathing Guide (4-7-8) | As a student, I want a visual 4-7-8 breathing exercise, so that I can calm down during peaks of anxiety. | Given high stress is detected, when the app is opened, then a guided breathing animation appears. | E3 |
| US25 | Micro-meditations | As a user, I want to access short meditation guides, so that I can focus during my work breaks. | Given the user has limited time, when they select a meditation, then the focus audio/guide plays. | E3 |
| US26 | System Feedback | As a user, I want to rate the AI's advice, so that the system learns what helps me the most. | Given a tip is received, when the user provides a star rating, then the AI adjusts future recommendations. | E3 |
| US27 | Hydration Alert | As a user, I want reminders to drink water, so that I don't neglect my physical health due to work. | Given 2 hours pass without a record, when the timer hits, then a subtle notification is sent to the mobile. | E3 |
| US28 | Habit Streak | As a user, I want to see my historical streak, so that I stay motivated and disciplined. | Given the user enters their profile, when they view stats, then the system shows their highest current streak. | E3 |
| US29 (T) | DB Indexing | As an engineer, I want to implement indexing on habits, so that the application loads lists quickly. | Given the system has thousands of records, when a query is executed, then the response time must be < 100ms. | E3 |
| US30 (T) | Offline Cache | As a developer, I want local data persistence, so that the user can write in their journal without an internet connection. | Given there is no connection, when a journal is saved, then it syncs automatically once signal is restored. | E3 |
| US31 | Analytics Dashboard | As a user, I want to see bar charts of my emotions, so that I can understand my weekly ups and downs. | Given the analytics panel is opened, when "Week" is selected, then the emotional bar for each day is displayed. | E4 |
| US32 | Word Cloud | As a user, I want to see my recurring keywords, so that I can identify my major stress triggers. | Given a month of usage data, when processing records, then a word cloud proportional to usage is displayed. | E4 |
| US33 | Premium Offers | As a user, I want to see a plan comparison, so that I can decide if I want to unlock extra features. | Given the user is on the free version, when they enter reports, then the benefits of going Premium are shown. | E4 |
| US34 | Secure Payment (Stripe) | As a user, I want to pay through a secure gateway, so that I can become Premium with total confidence. | Given a plan is chosen, when card details are entered, then the system activates the subscription instantly. | E4 |
| US35 | Export PDF | As a Premium user, I want a structured PDF history, so that I can share it formally with my psychologist. | Given the user is Premium, when they request an export, then a professional downloadable document is generated. | E4 |
| US36 | Export CSV | As a Premium user, I want to download my data in CSV, so that I can analyze it personally in Excel. | Given CSV format is selected, when confirmed, then the user receives a spreadsheet with their full history. | E4 |
| US37 | Technical Support | As a user, I want a direct help section, so that I can resolve technical questions about the application. | Given a bug is encountered, when support is messaged, then a service ticket number is issued. | E4 |
| US38 (T) | Unit Testing | As a developer, I want to implement automated tests, so that I can ensure payment flows never break. | Given code is modified, when tests are run, then 100% must pass green before committing. | E4 |
| US39 (T) | Responsiveness | As a developer, I want to use Flexbox and Grid, so that the app looks perfect on tablets and laptops. | Given the device changes, when the screen scales, then the UI adjusts without visual errors. | E4 |
| US40 (T) | Rate Limiting | As an admin, I want to implement API request limits, so that I can protect the server from abuse or external attacks. | Given an IP exceeds the request limit, when the threshold is met, then the system temporarily blocks access. | E4 |

## 3.2. Impact Mapping

---

## 3.3. Product Backlog

---

| # Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
|---------|--------------|--------|-------------|----------------------------------|
| | | | | |
