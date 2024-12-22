# 🚀 URL Shortener - Make Your Links Compact! 

![URL Shortener Banner](https://img.shields.io/badge/URL-Shortener-brightgreen)

## 🌟 [Try it Now!](https://suryanpaul.github.io/UrlShortener/)

## 📝 Description
A lightning-fast, user-friendly URL shortening service that transforms your long, unwieldy links into clean, shareable URLs.

## ✨ Features
- 🎯 Instant URL shortening
- 📱 Responsive design
- 📋 One-click copy to clipboard
- ⚡ No registration required
- 🔄 Real-time link generation
- 🌐 Works with any valid URL

## 🛠️ Tech Stack
- Frontend: HTML5, CSS3, JavaScript
- API: [Spoo.me API](https://spoo.me/api)
- Hosting: GitHub Pages

## 🎮 How to Use
1. Visit the [website](https://suryanpaul.github.io/UrlShortener/)
2. Paste your long URL
3. Click "Shorten"
4. Copy & share your shortened link!

## ⚠️ Limitations
- Daily API request limits
- No custom URL endings
- No analytics tracking
- No link expiration options

## 🔄 API Details
```javascript
API Endpoint: https://spoo.me/api/v1/shorten
Method: POST
Headers: {
    'Content-Type': 'application/json'
}
Body: {
    "url": "your-long-url"
}
Response: JSON with shortened URL
```

## 🚫 Known Issues
- Rate limiting on free tier
- API requires CORS handling
- Maximum URL length restrictions
- Service availability dependent on spoo.me uptime

## 📞 Support
Found a bug? Open an issue or contact us!

## 📜 License
MIT License - Feel free to use and modify!

---
Made with ❤️ by [Suryan Paul](https://github.com/suryanpaul)