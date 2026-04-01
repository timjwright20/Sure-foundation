🏛️ Sure Foundation
LDS Apologetics Trivia Challenge
A two-player trivia game designed to help Latter-day Saints practice responding to common criticisms and anti-Mormon arguments using LDS apologetic responses and scripture.

🎮 How to Play
Enter both player names on the setup screen
Take turns spinning the category wheel
Read the anti-Mormon criticism displayed on screen
Type your best LDS apologetic response in the text box
AI evaluates your answer — full points, half points, or zero
Earn bonus points by identifying the correct scripture reference
The player with the most points after 10 rounds wins!
⏱️ Scoring
Time to Answer	Points Earned
Under 2 minutes	10 points
2–3 minutes	8 points
3–4 minutes	6 points
4–5 minutes	4 points
Over 5 minutes	0 points
Partial answers receive half the available time points
Scripture bonus round awards an additional 10 points per question
If a player fails or skips, the other player gets a steal opportunity
📚 Categories
Category
📖	Book of Mormon
📜	Book of Abraham
⛪	Joseph Smith
💍	Polygamy
✊	Race & Priesthood
💰	Finances
🌈	Gender & LGBTQ
⚖️	Authority
🔮	Theology
📱	Modern Criticism
⚙️ Admin Panel
Click Admin Panel on the setup screen and enter the admin password to:

Add new questions to any category
Provide custom LDS apologetic answers
Link scripture references for the bonus round
🛠️ Tech Stack
Frontend: React (via CDN, no build tools required)
Backend: Vercel Serverless Functions (Node.js)
AI Evaluation: Anthropic Claude API (claude-sonnet-4-20250514)
Hosting: Vercel (free tier)
🚀 Deployment
Fork or clone this repository
Connect the repo to Vercel
Add your Anthropic API key as an environment variable:
Name: ANTHROPIC_API_KEY
Value: sk-ant-...
Deploy — Vercel handles the rest
📁 Project Structure
sure-foundation/
├── index.html          # Full game frontend (React via CDN)
├── vercel.json         # Vercel routing configuration
├── README.md           # This file
└── api/
    └── evaluate.js     # Serverless function — proxies Anthropic API calls
🔒 Security Note
The Anthropic API key is stored as a Vercel environment variable and is never exposed in the frontend source code. All API calls are routed through the serverless function in /api/evaluate.js.

✝️ Purpose
This game was created to help members of The Church of Jesus Christ of Latter-day Saints become more familiar with common criticisms of the faith and the well-documented apologetic responses available through resources like FAIR Mormon, Book of Mormon Central, and the Church's own Gospel Topics Essays.

"Always be prepared to give an answer to everyone who asks you to give the reason for the hope that you have." — 1 Peter 3:15

Built by Tim Wright | Powered by Claude AI

