# Pastetime Community & Support

Welcome to the official community and support repository for Pastetime, your developer-friendly suite for timestamp, timezone, and business days calculations.

## 🚀 What is Pastetime?

Pastetime is a collection of free, fast, and privacy-focused tools for:

* **Converting UTC timestamps to local time** (for any city)
* **Calculating business days** between dates (with custom weekends and holidays)
* **Translating timestamps** between ISO, Unix, RFC 2822, and more
* **🆕 REST API with Natural Language Processing** - Convert "tomorrow at 3pm" to any timezone

Check out the live app: <https://www.pastetime.com/>

## ✨ NEW: Developer API Available

Pastetime now includes a **powerful REST API** that understands natural language! Perfect for developers and automation tools.

### 🗣️ Natural Language Time Conversion
```bash
curl -X POST https://pastetime.com/api/convert \
  -H "Content-Type: application/json" \
  -d '{
    "when": "tomorrow at 3pm",
    "timezone": "America/New_York"
  }'
```

### 🔧 Key API Features
- **Natural Language**: "next Friday", "in 2 hours", "tomorrow at 3pm"
- **Zero Setup**: No API keys required (MVP phase)
- **Multiple Endpoints**: Time conversion, business days, timezone lists
- **Perfect for**: Zapier workflows, scheduling apps, automations

### 📖 Full API Documentation
👉 **[Complete API Docs & Examples](https://pastetime.com/api/docs)**

---

## 📣 Feedback, Bugs & Feature Requests

* **Found a bug?** Open an Issue
* **Have an idea or feature request?** Open a Feature Request
* **API feedback?** We'd love to hear how you're using our API!

I love hearing from users and developers—your feedback helps make Pastetime better for everyone.

---

## 📚 Documentation

* [Getting Started Guide](https://pastetime.com/guide)
* [Business Days Calculator](https://pastetime.com/business-days-calculator)
* [Understanding Timestamps](https://pastetime.com/blog)
* [**NEW: API Documentation**](https://pastetime.com/api/docs)

---

## ❤️ Support the Project

If Pastetime saves you time or headaches, you can show your appreciation here:

[![Donate with Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com) [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com)

Thank you for your support!

---

## 🛠️ Roadmap

* ✅ **Public API for integrations** (Zapier, etc.) - **LIVE NOW!**
* 🔄 Enhanced API features (webhooks, batch processing)
* 📅 More date/time calculators (durations, working hours)
* 📖 Enhanced developer docs & SDKs
* 🌟 Community-driven features

Want to help shape the future? Open a feature request or upvote an idea in Issues!

---

## 📣 Connect

* [Website](https://pastetime.com)
* [Blog](https://pastetime.com/blog)
* [API Documentation](https://pastetime.com/api/docs)
* [X (Twitter)](https://twitter.com)
* [DEV.to](https://dev.to)

---

> **Note:** This repository is for issues, feature requests, and community discussion. The main application code is in a separate private repository. Our **public API** is now live and available for all developers!

---

Thank you for using and supporting Pastetime! 🚀
