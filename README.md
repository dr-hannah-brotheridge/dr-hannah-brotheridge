# Hi, I'm Dr. Hannah Brotheridge 👋
### Clinical Product Creator

Having an MBChB background and a few years of experience as a doctor; I now design, architect, and evaluate AI systems and applications for healthcare.
I graduated from the University of Auckland as an undergraduate and have worked for Te Whatu Ora Waitaha as a house officer since 2024.

## MedList
- **https://med-list.flutterflow.app/**

## SignalHealth
- **https://signalhealth.dev/**

## Product Engineering & Deployment
- **Full-Stack PWA Architecture:** Designing and deploying Progressive Web Apps from concept to production.
- **DevOps & Deployment:** Continuous Integration and Continuous Delivery/Deployment (CI/CD) workflows using GitHub and Vercel for rapid iteration and hosting.
- **Database Management:** Architecting relational data models in Supabase (PostgreSQL), including Row Level Security (RLS) implementation for multi-user security.

## No-Code to Pro-Code Transition 
Proven experience scaling products from rapid no-code prototyping (Glide/FlutterFlow) to custom-coded Node.js applications using LLM assistance (Claude Code and Cline).

## AI & LLM Orchestration
- **Prompt Engineering & Safety:** Development of complex, state-based "Clinical Risk Engines" using multi-state prompt architecture to enforce strict guardrails, diagnostic locking, and safety-critical escalation and/or de-escalation paths.
- **LLM Integration:** Orchestrating API integrations with Anthropic (Claude) to create persistent, memory-augmented chatbots that maintain longitudinal health context.
- **Clinical Safety Logic:** Implementing "Anti-Over-Escalation" and "Source-of-Truth" protocols to ensure LLM behavior remains deterministic and safe in high-stakes environments.
- **LLM Cost Optimisation Techniques** Model cascading/Right-sizing for tasks, Context window management, Frequency Throttling/Batching and Prompt Caching. 

## Domain Expertise

- **Clinical AI Architecture:** Bridging the gap between clinical safety protocols and technical system design.
- **Health Tech Product Design:** Translating complex medical workflows (triage, history taking, medication management) into intuitive, patient-facing UX.

## Active Projects
- **SignalHealth PWA:** A highly bounded, deterministic multi-state prompt engine for user health patterns and tracking and efficient doctor check-ups.
- **MedList PWA:** A light, user-centric progressive web app for patient-friendly medication compliance, information and collation.

## My Aims
- **Patient Autonomy and Understanding** I aim to improve the understanding of an individual's own health by providing access to patient-centred language,
  information and health patterns/memory. This will increase adherence to treatment and management of conditions and help people take better control over their health.
  It will push society towards a proactive healthcare model instead of a current reactive model.
- **Prevention > Reaction** As said above, especially in an ageing population with reduced hospital beds, increased strain on doctors, and more people wanting to seek care; we
  need to be looking upstream at how people can get help. If we can improve the clinical safety and validity, the empathy and rapport of AI; then this tool
  will be indispensable.
- **Efficiency and utilisation of current care** I want to provide solutions to the minute amount of time people have to see their doctor. By allowing people to have
  summaries of their health data at home and on the go, lists of their medications in one absolute place, a generated report of the RELEVANT and PERTINENT info that
  doctors want - the treatment will be much better.











# SignalHealth PWA
**https://signalhealth.dev/**

## 🚀 Tech Stack

- **Runtime:** Node.js
- **Database & Auth:** Supabase (PostgreSQL with RLS)
- **Intelligence:** Anthropic API (Claude)
- **Deployment:** Vercel

## 🛠 Engineering Highlights

- **Clinical Control Engine:** Architected a deterministic logic layer utilizing 18+ pages of safety-critical prompts to manage complex health triage.
- **Longitudinal Memory:** Leveraged Supabase to maintain persistent, structured health profiles across sessions, transforming raw chat data into actionable longitudinal health narratives.
- **Security & Compliance:** Implemented a robust, RLS-protected authentication flow that enforces strict medical-risk guardrails during state-based conversations.

## 📱Key Features

### 🧠 The Chat Engine
- **Pre-Appointment Mode:** Syncs with upcoming appointments to help users articulate concerns, ensuring efficient doctor consultations.
- **Day-to-Day Mode:** Builds the user's health profile dynamically.
- **Safety Guardrails:** Real-time risk assessment; the engine triggers immediate alerts for emergency care or professional intervention when specific clinical criteria are met.

### 👤 Profile Hub
- **Health Story:** A living, comprehensive narrative that evolves with every conversation, categorizing symptoms and resolving problems. Downloadable as a PDF.
- **Gamified Onboarding:** A progress bar encourages data completion, improving the accuracy of future health insights.
- **Clinical Integration:** Visualizes standardized health questionnaires (AUDIT, Epworth, STOPBANG, PHQ9, GAD7, EPDS), pre-populating them for medical appointments to save valuable clinic time.

### 📋 GP Summary & Sharing
- **Real-Time Generation:** A summary that updates instantly based on profile changes and conversation history.
- **Clinical Readiness:** Provides condensed, high-value data for physicians.
- **Easy Export:** Built-in sharing capabilities (Email, Clipboard, Social) to ensure the user’s medical narrative is always at hand.

### ⚙️ Settings & Retention
- **Smart Notifications:** Customizable check-in frequency. Includes an automated "3-day symptom follow-up" feature to track patient progress and improve retention.
- **User Control:** Full suite of account management tools, including TOS, Privacy Policy, and medical disclaimers.
