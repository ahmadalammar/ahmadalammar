# SayaKahwin Social Media Posters 💒✨

Beautiful, catchy social media marketing posters for **sayakahwin.com** - the digital wedding card platform.

## 📁 What's Included

### Instagram Posts (1080x1080)
| File | Description | Hook/Angle |
|------|-------------|------------|
| `instagram-post-1.html` | Pink romantic design | "Still sending paper invites?" - Modernization angle |
| `instagram-post-2.html` | Elegant navy/gold design | Feature showcase - "Why 10,000+ Couples Choose Digital" |
| `instagram-post-3.html` | Purple gradient comparison | Paper vs Digital side-by-side comparison |

### Instagram Carousel (1080x1350)
| File | Description | Hook/Angle |
|------|-------------|------------|
| `instagram-carousel-slide.html` | Yellow energetic design | "3 Signs You Need a Digital Wedding Card" - Engagement bait |

### TikTok/Reels/Stories (1080x1920)
| File | Description | Hook/Angle |
|------|-------------|------------|
| `tiktok-story-1.html` | Romantic pink with phone mockup | "POV: Your wedding card is a link" |
| `tiktok-story-2.html` | Dark meme-style design | Relatable struggle format - "The Struggle is Real" |
| `tiktok-trendy.html` | Aesthetic Gen-Z minimal | "Make it aesthetic" - Trendy/viral style |

## 🎨 How to Export as Images

### Method 1: Browser Screenshot (Quickest)
1. Open any `.html` file in Chrome/Firefox
2. Press `F12` to open DevTools
3. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
4. Type "screenshot" and select "Capture full size screenshot"
5. Save the PNG file

### Method 2: Using Browser Print
1. Open the HTML file in browser
2. Press `Ctrl+P` (Print)
3. Choose "Save as PDF" 
4. Convert PDF to PNG using any converter

### Method 3: Using Puppeteer/Playwright (Automated)
```javascript
// Example with Puppeteer
const puppeteer = require('puppeteer');

async function screenshot() {
  const browser = await puppeteer.launch();
  const page = await browser.newPage();
  await page.setViewport({ width: 1080, height: 1080 });
  await page.goto('file://path/to/instagram-post-1.html');
  await page.screenshot({ path: 'poster.png' });
  await browser.close();
}
```

### Method 4: Online Tools
1. Go to [htmlcsstoimage.com](https://htmlcsstoimage.com)
2. Paste the HTML content
3. Download as PNG/JPG

## 📱 Posting Best Practices

### Instagram
- **Best times to post**: 11am-1pm, 7pm-9pm (local time)
- **Carousel posts** get 1.4x more reach than single images
- Use relevant hashtags: `#MalaysianWedding` `#DigitalWeddingCard` `#Kahwin2026` `#WeddingPlanning`

### TikTok
- **Vertical format** (1080x1920) is essential
- First 3 seconds must hook viewers
- Add trending sounds for more reach
- Use hashtags: `#wedding` `#weddingcard` `#weddingtok` `#malaysiawedding`

## 🎯 Marketing Copy Suggestions

### Instagram Captions

**For Post 1:**
```
Still printing wedding cards? 📜 

Here's the thing - it's 2026 and your guests are already on their phones 24/7. 

Why not meet them where they are?

✨ One beautiful link
✨ All your wedding details
✨ Instant RSVP tracking
✨ Eco-friendly (no paper waste!)

Create your digital wedding card FREE at sayakahwin.com 💍

#SayaKahwin #DigitalWeddingCard #MalaysianWedding #Kahwin2026
```

**For Post 3 (Comparison):**
```
Let's do the math 🧮

Paper invites:
❌ RM500-2000 printing
❌ Extra postage costs
❌ Manual RSVP tracking (hello Excel sheets)
❌ Can't update if venue changes

Digital with SayaKahwin:
✅ Start FREE
✅ Share via WhatsApp in seconds
✅ Auto RSVP tracking
✅ Edit anytime, anywhere

The choice is clear 💡

Link in bio 👆

#WeddingPlanning #DigitalInvitation #ModernWedding
```

### TikTok Video Ideas

1. **Transition video**: Show printing struggle → reveal beautiful digital card
2. **Voiceover**: "Things I wish I knew before my wedding" with digital card reveal
3. **Trending sound**: Use popular wedding sounds with card showcase
4. **Tutorial style**: "How to create your wedding card in 60 seconds"

## 🎨 Brand Colors Used

| Color | Hex | Usage |
|-------|-----|-------|
| Wedding Red | `#C53030` | Primary CTA, highlights |
| Gold | `#D4AF37` | Premium/elegant accent |
| Soft Pink | `#FED7D7` | Romantic backgrounds |
| Navy | `#1a1a2e` | Sophisticated dark theme |
| Purple | `#764ba2` | Modern gradient |

## 📐 Dimensions Reference

| Platform | Dimensions | Aspect Ratio |
|----------|------------|--------------|
| Instagram Square | 1080 x 1080 | 1:1 |
| Instagram Portrait | 1080 x 1350 | 4:5 |
| Instagram Story/Reels | 1080 x 1920 | 9:16 |
| TikTok | 1080 x 1920 | 9:16 |

## 💡 A/B Testing Ideas

1. Test different hooks: "Paper vs Digital" vs "Save Money" vs "Eco-Friendly"
2. Test CTA variations: "Create Yours FREE" vs "Get Started" vs "Try Now"
3. Test color schemes: Romantic pink vs Elegant gold vs Modern purple

---

Made with 💕 for **sayakahwin.com** - Your Digital Wedding Card Solution

*"Saya Kahwin" = "I'm Getting Married" in Malay*
