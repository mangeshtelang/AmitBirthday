# Amit Javali — 50th Birthday Digital Invitation (Version 2)

## 📁 Files Included
- `index.html` — Complete high-energy digital invitation with opening animation, music, 50-year quiz, venue gallery, map, 1-tap WhatsApp RSVP, and calendar export
- `amit-portrait.jpg` — Birthday boy Amit's smiling portrait
- `venue-rooftop.png` — Rude Lounge Powai open-air rooftop photo
- `venue-bar.jpg` — Rude Lounge Powai cocktail bar photo
- `preview.jpg` — WhatsApp/social share link preview image
- `index-v1.html` — Backup of the original Version 1

---

## ⚡ What is New in Version 2
1. 🎞️ **Opening Curtain Animation**: Tap "Open Invitation" to reveal the celebration with confetti.
2. 🎵 **Celebration Party Music**: Floating audio toggle with animated equalizer bars (Mute/Unmute).
3. 🥂 **Shimmering Animated "50"**: Eye-catching golden milestone graphic.
4. ⏳ **Live Countdown Timer**: Real-time ticker counting down to Saturday, 31 October 2026, 7:30 PM.
5. 🎯 **50-Years Quiz (Moved BEFORE Venue)**:
   - Placed right after the story so guests stay engaged.
   - Calculates real score out of 5 with confetti explosion.
   - Assigns fun badges (e.g. *Legendary Chaddi Buddy*, *Inner Circle VIP*).
   - Shows answers breakdown.
   - **"WhatsApp My Score to Amit"** 1-tap button.
6. 📸 **Actual Venue Photos**: Features Rude Lounge rooftop and cocktail bar visuals.
7. 🗺️ **Interactive Logistics**:
   - Copy address button with instant toast.
   - 1-tap Google Maps directions.
   - Uber & Ola ride booking links.
   - Dark-styled embedded interactive map.
8. 📲 **1-Tap WhatsApp RSVP**:
   - Guests can choose (Solo / With +1) and tap to send a pre-filled confirmation to Amit.
9. 📅 **Add to Calendar**:
   - 1-click Google Calendar integration.
   - Apple Calendar / Outlook `.ics` instant file download.
10. 🔗 **Share Invitation**:
    - Mobile native share sheet or 1-tap link copy.

---

## ⚙️ Quick Customization (Optional)
In `index.html`, search for `EVENT_CONFIG` (around line 695):

```javascript
const EVENT_CONFIG = {
  name: "Amit Javali",
  dateStr: "2026-10-31T19:30:00+05:30",
  venueName: "Rude Lounge, Powai",
  address: "B-Wing, Supreme Business Park, 8, South Avenue, Hiranandani Gardens, Powai, Mumbai 400076",
  mapsUrl: "https://maps.app.goo.gl/M5gQCP8AaDsvXMwd7",
  
  // Set Amit's WhatsApp number with country code (e.g., '919820000000').
  // If left as "", WhatsApp will open the contact list to let guests select Amit.
  whatsappNumber: "", 

  // Customize quiz correct answers here if desired:
  correctAnswers: {
    q1: "Friends",   // 🥂 Catch up with friends
    q2: "Black",     // 🖤 Classic Black
    q3: "Music",     // 🎵 Vibing to music
    q4: "Anything",  // 😋 Anything delicious with friends
    q5: "Friends"    // ❤️ Friends & Brotherhood
  }
};
```

---

## 🚀 Vercel Deployment (Easiest Method)

1. Go to https://vercel.com/ and sign in.
2. If uploading via GitHub:
   - Create a GitHub repository (e.g. `amit-50th-bash`).
   - Push all files (`index.html`, `amit-portrait.jpg`, `venue-rooftop.png`, `venue-bar.jpg`, `preview.jpg`).
   - Import into Vercel and click **Deploy**.
3. OR use Vercel CLI / Drag-and-drop:
   - Run `npx vercel` in this folder.
4. Your live link will be ready in seconds: `https://your-project.vercel.app`

---

## 📲 WhatsApp Invite Message Template

Copy and paste this message into WhatsApp alongside your link:

```
🎉 *Amit is turning 50!* 🥂

49 years completed… and now officially stepping into the big 5-0! 😎

Join us for an evening of nostalgic school stories, cocktails, great music, and endless laughs.

👇 *Open your digital invitation:*
https://YOUR-VERCEL-LINK.vercel.app

✨ *Inside:*
• 🎯 The "How well do you really know Amit?" 50-year quiz
• 📍 Venue photos, rooftop vibe & Google Maps
• 📲 1-tap WhatsApp RSVP & Calendar reminder

See you on *Saturday, 31 October 2026* at Rude Lounge, Powai! 🍻
```
