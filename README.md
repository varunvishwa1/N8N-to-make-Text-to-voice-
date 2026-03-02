# N8N-to-make-Text-to-voice-


PodGen AI
From Idea to Published Podcast in Minutes

PodGen AI is an AI-powered podcast generation engine designed to remove friction from content creation.

As a founder, I built this with one simple belief: creating high-quality audio content should not require expensive equipment, editing skills, or hours of production time.

Give it a topic.
It delivers a professionally written script and studio-quality voice output automatically.

🚀 Why I Built This

Podcasting is powerful.
But the production process slows creators down.

Script writing takes time.
Recording demands clarity and confidence.
Editing requires tools and patience.

Most ideas never become episodes.

PodGen AI removes those barriers.

💡 What It Does

• Generates a conversational, listener-friendly podcast script
• Keeps content optimized for ~2-minute engagement
• Converts text into realistic AI voice
• Returns ready-to-stream audio
• Runs fully automated through n8n

No manual scripting.
No recording setup.
No post-production headaches.

🧠 How It Works

The system is built as a modular automation pipeline:

A topic is submitted via chat or webhook

Google Gemini generates a structured podcast script

The script is sent to Murf AI

Murf converts it into natural speech

Audio is streamed back as output

The architecture is designed to be scalable and easily extendable.

🏗️ Technology Stack

n8n – Workflow automation engine

Google Gemini (PaLM API) – AI content generation

Murf AI API – Text-to-speech synthesis

REST API integrations

📦 Setup
Install n8n
npm install n8n -g
n8n start

Or deploy via Docker.

Import Workflow

Open n8n

Select “Import Workflow”

Upload the JSON file

Configure Credentials

Add:

Google Gemini API key

Murf AI API key

Use environment variables or n8n credentials. Never expose keys publicly.

🎯 Use Case

Input:
“The impact of AI on small businesses”

Output:
• Professionally written podcast script
• High-quality AI voice audio
• Ready-to-share episode

📈 Vision

PodGen AI is more than a workflow.

It’s the foundation for a scalable AI-driven audio content platform.

Future direction includes:

• Multi-voice and multilingual support
• Background music layering
• Auto episode metadata generation
• Direct publishing to podcast platforms
• Web-based creator dashboard
• SaaS deployment

The long-term goal is simple:
Make podcast production instant and accessible to everyone.

👤 Founder’s Note

This project represents my commitment to building intelligent automation systems that reduce creative friction.

PodGen AI demonstrates how AI, when combined with thoughtful workflow design, can replace complex manual processes with a simple and elegant solution.

This is just the beginning.
