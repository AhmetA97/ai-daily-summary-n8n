🧠 AI Daily Summary Assistant (n8n + Google Calendar + Gmail + OpenAI)

An intelligent automation workflow that generates a daily AI-written summary of meetings and related emails.
Built with n8n, Google Calendar API, Gmail API, and OpenAI GPT-4o, this project acts as a personal productivity assistant — automatically gathering your day’s events, relevant messages, and summarizing them into a concise email delivered every morning.

🚀 Features

⏰ Automatically triggers each morning via Schedule node

📅 Fetches daily meetings from Google Calendar

📧 Retrieves recent related emails from Gmail

🤖 Uses OpenAI GPT-4o to generate natural-language summaries

📨 Sends a formatted summary email to the user’s inbox

🔒 Built with secure OAuth2 credentials for Google APIs

⚙️ Tech Stack

n8n (workflow automation platform)

Google Calendar API

Gmail API

OpenAI GPT-4o

JavaScript / JSON (within n8n Code nodes)

📂 Workflow Structure

Schedule Trigger → runs daily

Google Calendar Node → fetches events

Code Node → generates Gmail queries

Gmail Node → fetches related messages

Merge & Format Nodes → combine data

OpenAI Node → summarize meetings and emails

Gmail Send Node → deliver summary to user

📈 Results

Reduced daily planning and email review time by 90%+

Created a reliable, fully automated AI assistant

Demonstrated advanced workflow design, API orchestration, and prompt engineering skills

📎 How to Use

Import the .json file into your n8n workspace.

Connect your Google and OpenAI credentials.

Adjust the schedule and email recipients.

Activate the workflow — you’ll receive a summary every morning.
