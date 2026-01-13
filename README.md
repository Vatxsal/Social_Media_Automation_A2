# AI-Powered RSS to Social Media Automation (Free APIs)

An end-to-end automation system that converts RSS articles into **AI-generated LinkedIn and Instagram content**, complete with **captions and images**, using **100% free APIs**.

Built with ❤️ using Make.com, Groq AI, and Google Sheets.

---

## Features

- RSS feed ingestion
- AI article summarization (Groq – Free)
- Platform-specific captions (LinkedIn & Instagram)
- AI image generation (Free)
- Google Sheets as content database
- Duplicate prevention using smart filtering
- Router-based multi-platform logic
- No paid APIs required

---

## Tech Stack (Free Only)

- **Automation:** Make.com
- **AI Text:** Groq API (Free tier)
- **AI Images:** Pollinations.ai
- **Storage:** Google Sheets
- **Input:** RSS Feeds

---

## How It Works

RSS Feed → AI Summary → Router
├── LinkedIn → Image → Sheet

├── Instagram → Image → Sheet

Each article is processed once and duplicates are automatically blocked.

---

## Google Sheets Structure

| Column | Description |
|------|------------|
| Platform | LinkedIn / Instagram |
| Caption | AI-generated caption |
| Image URL | Generated image link |
| Original_URL | RSS article link |
| Date | Automation run time |

---

## Duplicate Protection

The system checks if an RSS article already exists in Google Sheets before inserting a new row, ensuring **no duplicate content**, even if AI captions change.

---

## Screenshots & Workflow

This repository includes:
- Full Make.com workflow screenshots
- Module configuration screenshots
- Google Sheets examples

Refer to the `/screenshots` folder for complete visual documentation.

---

## Who Is This For?

- Students learning automation
- Indie developers
- Content creators
- Social media managers
- Anyone wanting AI automation without paid APIs

---

## Future Improvements

- Auto-posting to social platforms
- Carousel & reel generation
- Hashtag automation
- Scheduling & analytics
- Multi-language support

---

## License

This project is open for learning and experimentation.


If you find this useful, consider starring the repo ⭐
