# 🎂 Birthday Website — How to Run

## Quick Start (Zero Setup Needed!)

### Option 1: Double-click to open (Easiest)
1. Unzip the folder
2. Open the `birthday-website/` folder
3. **Double-click `index.html`**
4. It opens in your browser — done! ✅

### Option 2: Use VS Code Live Server (Best Experience)
1. Install [VS Code](https://code.visualstudio.com/)
2. Install the **Live Server** extension (by Ritwick Dey)
3. Open `index.html` in VS Code
4. Click **"Go Live"** at the bottom-right
5. Opens at `http://127.0.0.1:5500`

### Option 3: Python Local Server
```bash
cd birthday-website
python3 -m http.server 8080
```
Then open: http://localhost:8080

---

## 📁 File Structure
```
birthday-website/
└── index.html     ← The entire website (self-contained)
```

## 🎨 How to Customize

### Change the Name
In `index.html`, find:
```html
<h1 class="birthday-title">Happy Birthday ❤️ Jaan</h1>
```
Replace **Jaan** with your person's name.

### Change the Letter
Find `const letterBody = \`...\`` and edit the text.

### Add Real Photos
In the gallery section, replace the `gallery-placeholder` div with an `<img>` tag:
```html
<img src="your-photo.jpg" alt="caption">
```
Place your photos in the same folder as `index.html`.

### Change the Signature
Find `sig.textContent = '— With all my love 💕';` and edit it.

---

## 🎵 Music
Click the 🎵 button (top-right) to toggle ambient chime music.
It's generated live — no audio file needed!

---

## 📱 Mobile
Works perfectly on phones and tablets — fully responsive!

---

Made with ❤️ — Built to make someone feel special.
