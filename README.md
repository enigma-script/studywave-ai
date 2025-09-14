# studywave-ai
AI-Powered Study OS for Indian Students | OpenAI x NxtWave Buildathon MVP
StudyWave: AI-Powered Study OS for Desi Dreamers
Welcome to StudyWave, an AI-driven study ecosystem designed to transform the academic journey for India's 40M university students (and beyond!). Built by Khadeejah Shaikh, a 3rd-year B.E. IT student, this project tackles uni burnout, procrastination, and fragmented learning with personalized, multimodal tools. Inspired by the OpenAI x NxtWave Buildathon, it’s my solo MVP—open for co-creation with peers, alumni, and the next gen!
🚀 Project Overview
StudyWave blends AI (OpenAI APIs) with Atomic Habits principles to:

Explain Concepts: Feynman-style narration + DALL-E diagrams (multilingual, e.g., Tamil with Pongal refs).
Build Habits: 2-min nudges, flashcards, Pomodoro, walk-quizzes with cultural streaks (e.g., Diwali badges).
Coordinate Groups: Whisper transcriptions + GPT task assignment.
Navigate Welfare: Voice-driven scholarship/internship matches from data.gov.in.

Goal: Scale to 10M users via college networks and TikTok challenges, evolving into a startup-ready platform.
🛠️ Tech Stack

Frontend/UI: Streamlit (Python-based, simple chat UI).
Backend/AI: OpenAI APIs (GPT-4o, DALL-E, Whisper) + LangChain for prompt chaining.
Workflow: n8n for automation (e.g., welfare scrapes).
Hosting: Hugging Face Spaces (free deploy).
Data: Local JSON (habits/streaks); future: Firebase.

📋 Build Timeline

Week 1 (Sep 14-20): Prototype API scripts (text-to-diagram).
Week 2 (Sep 21-27): MVP UI + demo video.
Week 3 (Sep 28-Oct 4): Add voice/welfare features.
Week 4 (Oct 5-11): Scale mocks + GitHub launch.

🚧 Constraints & Mitigations

API Limits: Mitigated with caching (Hugging Face).
No GPU: Relies on pre-trained OpenAI models.
Time: Balanced with uni (Pomodoro sprints).

🎥 Demo

Hugging Face Spaces (forthcoming Week 2): Screenshots of UI flow (query → diagram → nudge).
Video: 1-min demo (post-Week 2).

🌱 Getting Started

Clone Repo: git clone https://github.com/khadeejahshaikh/studywave-mvp.git
Install Dependencies: pip install streamlit openai langchain n8n
Set API Keys: Create .env with OPENAI_API_KEY=your_key_here.
Run Locally: streamlit run app.py
Explore: Test with a query (e.g., "Explain binary search in Hindi").

🤝 Contribute

Fork this repo, tweak prompts, or add features (e.g., Notion integration).
Submit PRs—let’s co-build India’s AI edtech future!
Contact: khadeejahshaikh@example.com

📚 References

YouTube: 'NotebookLM Will Change How You Learn' - https://www.youtube.com
YouTube: 'YouTube Analytics Streaming Pipeline' - https://youtu.be/-Nl6hz2nYFA?si=GCikO3ayvl-jAxvd
GitHub: 'HabitRPG/habitica' - https://github.com/HabitRPG/habitica
GitHub: 'iSoron/uhabits' - https://github.com/iSoron/uhabits
GitHub: 'keshavgbpecdelhi/Web-Development' - https://github.com/keshavgbpecdelhi/Web-Development

🎉 Acknowledgments
Thanks to OpenAI x NxtWave for the workshop inspo and Grok (xAI) for my productivity hack—check my transformation story in the PPT!
