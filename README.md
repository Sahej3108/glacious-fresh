# Glacious Fresh™ — Website

> By Gale Worldwide Movers Pvt. Ltd.

## Pages Included
- Home
- About Us
- Services (Frozen Food Transport + Pan-India Coverage)
- FAQ
- Payment / Bank Details (SBI QR + UPI)
- Contact
- Book Shipment

---

## 🚀 Deploy to Vercel (Step-by-Step)

### Option 1: Drag & Drop (Easiest — No Coding)

1. Go to [https://vercel.com](https://vercel.com) and sign up / log in (free account).
2. Click **"Add New Project"** → **"Deploy from a folder"**
3. Drag and drop the **entire `glacious-fresh` folder** (this folder).
4. Vercel will auto-detect it as a static site.
5. Click **Deploy** — done! You'll get a live URL like `glacious-fresh.vercel.app`.

---

### Option 2: GitHub + Vercel (Recommended for updates)

1. Create a free account on [https://github.com](https://github.com)
2. Create a new repository called `glacious-fresh`
3. Upload both files (`index.html` and `vercel.json`) to the repo
4. Go to [https://vercel.com](https://vercel.com) → **"Add New Project"**
5. Connect your GitHub account and select the `glacious-fresh` repo
6. Click **Deploy**

Every time you push updates to GitHub, Vercel will auto-redeploy.

---

### Option 3: Vercel CLI

```bash
npm install -g vercel
cd glacious-fresh
vercel --prod
```

---

## 🛠 Customisation Before Deploying

### Add your real Bank Account Number & IFSC
Open `index.html` and find these two lines (around line 340):
```html
<span class="value" id="acct-num">Contact us for account details</span>
<span class="value" id="ifsc-code">Contact us for IFSC</span>
```
Replace the text inside with your real SBI account number and IFSC code.

### Add your real QR Code image
Replace the SVG QR placeholder with:
```html
<img src="your-qr-image.png" style="width:200px;height:200px;" alt="Scan to Pay">
```
Upload your `galeworldwide_sbi.pdf` QR as a PNG image and place it in the same folder.

---

## 📁 Files
- `index.html` — Full website (all 7 pages)
- `vercel.json` — Vercel routing config
- `README.md` — This file

---

**Contact:** rekha@galebestways.com | +91 8826175064
