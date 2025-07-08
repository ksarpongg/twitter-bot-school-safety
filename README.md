# 🛡️ SafeSchoolsBot: Twitter bot for school weapong violence monitoring in Ghana

This bot was designed to monitor Twitter for keywords like **"school", "student", "gun", "pistol", "weapon", and "Ghana"**, and automatically retweet posts that highlight safety concerns in schools. 

🚫 Due to recent Twitter API pricing changes, this bot cannot be run in production without a $100/month plan. However, the code works locally and is open-source for public interest, research, and journalism.

## 🔍 How it Works
- Searches for tweets with specific keywords (e.g. `school gun Ghana`)
- Retweets relevant posts (local only)
- Built using [Tweepy](https://www.tweepy.org/) and Python

## 🔐 Setup

1. Clone the repo
2. Create your `.env` file (see `.env.sample`)
3. Install dependencies:

