# n8n Social Media Agent 🤖

Just scrapes news, drafts a Facebook post, and generates an image. Built for my internship at medmind technology limited, a medtech startup.

---

## 📌 What it does

- **Scrapes** RSS news about dementia and physical rehab (daily schedule trigger).
- **Filters** the scraped content using an AIDA relevance check (so it doesn't post random junk).
- **Drafts** a Facebook post tailored for caregivers/elderly (aged 40–70) and mentions our company product naturally.
- **Generates** an image by passing a distilled prompt to the Flux model (triggered once content is marked as "post").

---

## ⚙️ Tech Stack

- **n8n** – workflow automation
- **RSS feeds** – generic news sources
- **Flux** – image generation model
- **Facebook API** – for posting (manual approval for now)

---

## 📊 Impact

- ~100–200 reach per post
- ~0.5–1 new follower per post
- API cost: basically $0.00x per run (very cheap)

---

## 🧑‍💻 Setup (if you want to try)

1. Import the JSON workflows into n8n.
2. Add your RSS feed URLs.
3. Set up your Flux API key.
4. Connect Facebook page (with permissions).
5. The workflow drafts everything – just copy the output to Facebook for now.

---

## 🚧 Current Status

The drafting pipeline is fully automated.  

