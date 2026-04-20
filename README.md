# GK Realty — Exhibition QR Setup

Do files banaye hain:

## 1. `index.html` — Landing Page
Ye wo page hai jo log QR scan karne ke baad dekhenge. Isme hai:
- **WhatsApp Chat button** (pre-filled message ke saath)
- **Instagram Follow button**
- **Direct Call button**
- Premium gold + dark design (builder/realty theme)

## 2. `qr-generator.html` — QR Code Banane ke liye
Browser me open karo, URL paste karo, QR download karo.

---

## 🚀 Setup Steps (10 minute)

### Step 1: Landing page host karo (Free)

**Option A — GitHub Pages (Recommended):**
1. https://github.com par account banao
2. New repository banao (public) — naam: `gk-realty`
3. `index.html` upload karo
4. Settings → Pages → Source: `main` branch → Save
5. 1-2 minute me URL milega: `https://yourusername.github.io/gk-realty/`

**Option B — Netlify Drop (Fastest):**
1. https://app.netlify.com/drop par jao
2. `index.html` file drag-drop karo
3. Turant URL mil jayega (e.g. `https://random-name.netlify.app`)

**Option C — Local test (only):**
`index.html` ko browser me direct open karke dekh sakte ho, but QR ke liye online URL chahiye.

### Step 2: QR generate karo
1. `qr-generator.html` browser me open karo
2. Upar wale field me **Step 1 ka URL** paste karo
3. Size **800×800** select karo (print ke liye best)
4. **Generate QR** → **Download PNG**

### Step 3: Print karo
- Minimum **4×4 inch** (10×10 cm) size me print karo
- **Laminate** karwao (exhibition me hath lagega)
- Banner/standee ke saath — QR ke niche bada likho: **"Scan for WhatsApp & Instagram"**

---

## 📝 Customize karna ho to

`index.html` me ye values change kar sakte ho:
- Line ~100: Logo text (`GK`)
- Line ~102: Company name (`GK Realty`)
- Line ~103: Tagline
- Line ~108: Welcome text
- WhatsApp number / Instagram link already set hain

---

## 💡 Pro Tips

1. **Short URL** banao (bit.ly / tinyurl) — QR chota aur clean dikhega
2. **QR ke niche** likho:
   - "Scan karke humse judiye"
   - "WhatsApp • Instagram • Call"
3. **High contrast** — black QR on white background
4. **Test karo** exhibition se pehle — 5 different phones se scan kar ke check karo
5. **Backup**: QR ke saath phone number bhi print karo (agar kisi ka camera work na kare)

---

## 📞 Contact Info (already configured)
- **WhatsApp:** +91 98989 37565
- **Instagram:** @gk_.realty
